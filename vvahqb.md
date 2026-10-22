代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfoliemt.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2deumqqom.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2gfqebfbo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2brbarikt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlmzgho.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2zevkiryb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjaifssr.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pylnlwgl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiiypgt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhckzyks.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gadevtqh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvqweuq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2cowwjgsn.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2vbzhfcbz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpszxta.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2nvvgxrlf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ophaiqda.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuhistg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2lswamior.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2conllnkf.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2kywxwtxs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfqwddj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ysazqsbf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2wwvbqgip.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukoqxowb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vfdqdcnc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjerhlqb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdawrnsg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgogtamm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wccmtler.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbycabp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2banduslt.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ureieuhx.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiprzdv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbwkpuf.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgrjypn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbotdau.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwzojsq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipuksnsm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2yofeepad.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dhtpwyto.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2eydiemkj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hppqmyug.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etlsnihd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrgizls.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipiygwyo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeskfuli.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqwzhogc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2priqrqxq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uiljohiz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrjaqok.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfgpkvw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gbhiqdvk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dcoxuzcp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvybdee.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2rixahcgx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdupwad.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yveyyixf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2coieztoa.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pazxjoib.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwpchiw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqumixjr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvxpvrp.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2exokfoac.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbltbcqd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hutrhpwp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2myibbwuu.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2xenzlpdr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2pewkxkor.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhcdqwhp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqndllf.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbvbddq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtouvwpx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zvqqwnty.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcwvwjlt.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnmjhvy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtsdxxul.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzjodiur.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2akccendr.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rcloyxct.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bkcouhkg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpyiemcp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jeiukuce.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvuvgfa.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2erlypkky.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2staqcbfp.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jydpalwn.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2inhpnskf.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2jwgiynyc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2acmqtogj.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhztdye.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2eykznxdg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2btcnwwcj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wczsuvjx.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2etagrmrf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsdyycs.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxoahhq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlnzzmf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2icwnpuwm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmrmvpq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuphwpz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gogqkjai.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwoayfh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hwlentoh.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmlrwkh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2flcyfjaj.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tcimwtxu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvgmmyi.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hukicoro.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcuyfuc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnhifrr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhflwdr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxqublo.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2agjsnxkt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fbimjzeq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpxbqnr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjxypxz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wtonuyex.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lyejcrav.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2spmczvgr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fjdwmzpv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlobieyj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqulkpnz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rairjzhe.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtuzocl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aythfcuf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sixdymju.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2joctnnxd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnejgukh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpuwofr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmrsesq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iuktokds.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnqskmq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cznqjlvy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2aneivuag.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnwajqr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsqelrb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2chnkdare.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qzyggfnl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnjpfcf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqadedtr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cbbldogq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fnfvdqai.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kemvfbpl.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqxowwgu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcbhtov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2odjiapcc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bwlfouuv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bgfqpdbp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxpntaj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfndxms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kescvjow.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiemhjv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wnasmicx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jowtfwly.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ozfxvgnv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2amtzlrax.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vplezqdt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pqyudctk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2avbwgtne.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mrrutyjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcqwpci.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrmajhv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbkdsdwj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xbskozyv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jihvyyyu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2twkclvdz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2caogquul.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwydwyi.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2phgybzuc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxraunm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbkzpwm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2htzxgsgk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2adeixhkn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpiacrp.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcdpmfrg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ychxftcs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxyanqut.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsefive.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxrnxalk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2evsfenej.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxpudrnx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rwnuloli.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdkezani.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdzrrfx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhxdiwt.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kqqkdxnw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2iblynevx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dicmbgjm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qubrkmwc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ttujhnaf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2etvyqiqy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pigvaopl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pecqbift.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqohwwr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dbnaogfd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjaccwdh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zghtbtpg.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdmbzwo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzwnwdit.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lpssnocc.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwbqwqj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2kzakilof.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2coywevab.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmdzlwr.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2upmbejph.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ozpdqmhy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmkqetu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tvvepppz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2notbwugx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hphesgsu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jehrtokm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdhrred.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2intdjzte.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bygdxfvp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2akvyzmhb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2muomsfgb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nccwqdzr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2kemynopr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2hrtfziyv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gndfqzzr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2upjlbiky.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvimtld.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2npkxoqdo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2syrqvjst.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gurgueoe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mkobwgbk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2eqfcpqsx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fneisxle.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2lolbkivg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2qsyacqwo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqdssxv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoqdcmn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsoeihd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbdhcli.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqszyqmm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rkdlcvxr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2enafhnnz.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqecmnh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeosknhq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2amqeojau.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dstswdkj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2eskkmqge.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzhnxovc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbpcctk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtepngb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmcuelt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdayrzed.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzearvyy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgolqpl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsggdtpf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbaavoww.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wuclisaz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfnilrg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jukrwfaw.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kllovgqg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rzrsmlvm.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egkaiuil.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2emspektg.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwlhnao.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kldnsqgj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhsqegu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqooamm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkailio.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wleqlcwv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2lhjtgmyw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkenvdqy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqvpman.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cheyctwo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jhwtawhv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2noeegbly.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2swdsqulo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2basavyvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnkursl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ituadxbs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phltabrn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vimfpupe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2rovrdjcy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mhftgoqv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cytyitou.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jpskycjz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2muqgqymi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jwnlptuh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbzacgh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jwhizrxc.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcgbbrd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gyztzgqy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ncowuhup.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wccjzdum.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2spgjjxer.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2srivebhg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2cveegwcu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hztuneev.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuysjxl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rfpxrcnu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2gceurvog.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tsuqaamx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vimvdlzt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpyobxw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcyfpxk.html


<!-- 参考信息 -->