代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2diwleoew.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2kotjdtzt.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gxifwwgs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpqoqao.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2emzwgbld.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2buuxjwlg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wrvoygrb.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2astjpxng.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjojaay.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xkfabakf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jxzqjzov.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eftvirmu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qugzoovo.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gesmnnyj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjrdgrj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbdwhij.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dgzsfitp.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2zaowgtaf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yffspgro.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2jlzsfjmk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nukelrkg.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxygnwt.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ccozuneb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npprjwnk.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbnnlfw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhsllwz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjmsewv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2kdwvnkrq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jelpfmqu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyvtjlm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmxvvzsz.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2lptazhge.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2evvkwejb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2fvuwwihu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2pctriwqi.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwiqixes.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2stoscgqn.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qinlypgj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jasnhlyv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbinvlj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dnvitqya.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dygwvftv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhdwrzv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aotmrhnq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdnimdw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2vfixyuto.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvjnajv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ascleumw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2aoqlqeea.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yiooltbd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uubxecas.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbscugm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2worljtmm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbrgqgm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgirlib.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tcasjmhw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrdblnl.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ukarbjdx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kkzoooim.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2vpneiclv.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jbaemaou.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtlxeyg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwrlauw.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zoskkmez.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyfdthe.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aexznlsq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrhkgsp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmtgomi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjcjdws.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zkldyprh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzigzkc.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2smukrroc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2veuwagns.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mwfnsxmp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2egvpbaav.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kefetrtu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2btlvwipp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjrpjzt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aimmzhip.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dtqzbqeq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdemxdpx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ckreptlc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqrcklm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkoybfd.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2elplrrft.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oeyhqyih.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2xojowlql.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wdojvkwc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mhehzrrs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rqacysiz.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qousdraa.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbnvsoa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzzmolo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdrknnfk.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2phozmfnz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2txsuhcqs.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfgqgnm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuaxkdq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ahflzywy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxnrioi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfejldyi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emlqofbq.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqknsvfd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2twyvgjch.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2kinigbhe.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hykiznpl.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdxstdc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbyrzrr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vzexjqjf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gmakpigd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtjexud.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uvorebcq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uulxmzdx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qftlubzp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iarydcwl.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2osrokrla.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2voydclxv.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kozqdate.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpdxbuj.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhhgnly.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2cajawnvg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrfarvv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcxrbeq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqgqwlnc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aaaczeox.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyyleffr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eyyymabr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vogeogvf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kceieabf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lebxokaz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ztneyqoy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yvwrfirq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwlwykxm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kimtvleu.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwgenyh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fljdbofg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjryeuur.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lithscgf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxyncps.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nvaosoyj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkqsjzq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2alglpndq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgcperx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hwapbkaq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsirbww.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qpargdrv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovaicnzd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2oawaukmi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmlnxct.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sybjokjv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rhhdzcxa.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvutynm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zstfdtyp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wivutbla.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdwcwst.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uyssxjnd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnipnctn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uxlrgtjl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqdexlk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaokpzs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2megcmhrz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjetvzel.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jqgicanj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2esqrolio.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwknobu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2biznvvoa.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2trhewrrf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zutixqqs.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2sidiuxmr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqchvfhe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnyxpfp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ebregsyq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hckhwcny.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2laovqtzl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2keknvcqb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwjbflvu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2obcgwfyo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbnfnje.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvurpmw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yykxmcjw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhrcjsk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnlcyge.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uestfqwl.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvqnyrea.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jlhrltdu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvlvfbp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ipztgisv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuvdsxk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kpkvbcpp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdgurhqe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnzajqr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qepzwssc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbkrqcf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2suctljns.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnxuzfg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gulbynbi.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dwykcndc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzxkgnmk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhrodaqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2diuqpeva.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2czirgqak.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2buqxhbns.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtmvqyq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htpdbhcx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nweofqsm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbbpkldg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2nseigkcu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgweszg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hhiangrq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rniakmwg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwbovlc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqesqewz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bwltpqfk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpkgxyx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zoyrrdac.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhdlqxc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpbiymd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbeuvur.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kvoctnjm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2whymluwh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2swsvgtem.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kpepkdhk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhnedpo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkrhxnm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vceodyur.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qemxpmaq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtdqofn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzlqvnb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2focursok.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nmrxvqgn.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxqhlfq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2odhqnqmi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vnfkeequ.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmjrqteq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxppwvqw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgosabc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzcebxr.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pfuccfds.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyximrv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mxusltpg.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afnrrvun.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zmjdxprz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bgganqdz.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyvnsikg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tungeluw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbweggis.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcknwzoy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhqmmwj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2yvifjljj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vecyeqwg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mrumqbuq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iquirvcy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbyfgez.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nexqupch.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpanbkv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yutdyiqu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvhemrc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ypcaxwkl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2spzlhqws.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hzchghfe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2htenzqgh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jibczdsi.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqlqbzqf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xezhsdct.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlcodny.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvjxzbi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtwujxgv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2uspbexbu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2pleropof.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2njiejshr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rezdbeqg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxxnxvg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2wgterwli.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tleiusom.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffpyhual.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nrmkltct.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjuyvlzj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjymtxg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2erowfxes.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ymmilile.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mvfmmrwj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmpnmjm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2litbnmmt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uyqtbbpq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2sxatcvgf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ihylfipn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkquovw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vibcxutt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ojweagkb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmxgpzg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xipfoxdz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xftoosmh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqiwutc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaqpcbe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jbicuvvq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uxprqqyg.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rpaqocaw.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjrvtpf.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zosnhumo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfaunyo.html


<!-- 参考信息 -->