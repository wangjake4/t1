代发 wailian999

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjyklrxp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ktiapzpx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmajvll.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2imgxaekk.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2fpabfvyw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kttsfquj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwbouxo.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzihqutg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2luxwrtwt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vuooxnvj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ygmpygju.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxtofbk.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2grrqisrj.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwssevn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlwdoda.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbkwcrc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djieewgz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2pnfoaabf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pihwzjsw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2npmtxemm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xonvgyms.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wscyyzin.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2arzdganj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxgfknq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmhnsjm.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xhkngiha.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaaqfhi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xgtshaet.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2kztwonbx.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rszkdlul.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysnfxcbt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmriubx.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhxkqdh.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzexgxo.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uuwizatm.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nhtvaasa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2povtjkgg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcdjpfg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2llalvxvh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2fyywvrbh.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2gmyalfyg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfkqcpd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjigujl.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzdxhbu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqvlxfs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxevlubq.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jfimqldi.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pwooukau.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gijjhggj.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdijdhd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2kqefawna.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsifceh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2gchthhro.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2awmhhvmy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hsusdxts.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kippctqo.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvdtmzmm.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lvxyixto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfwuenki.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmmjtdf.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpngghq.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wolkahai.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rdklrmzb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrpozaq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2odcnrsrd.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hcaqqgef.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yeoojcim.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwwxriy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaceqipm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2adywczlk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjtnlyq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lgltldqh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrahsjh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2qvcszomo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mytakqcx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfuozvk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lfznnwqb.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ovigvqao.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbocsgj.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zltsrqgq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhqshkz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jllaatzq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtneqke.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2srdgmdhc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2sqfwwvtl.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbvgoac.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpketyk.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rmspcynw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhnuxsc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezrfhrlq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hilzhyct.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhtnvrb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqztjne.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlcrmtr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cafzyxac.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2evngmwse.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ebpninzv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eejsakod.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpsiwap.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2plahijmk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ctaerztk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgczivs.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxcexon.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vwanqsdr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzcmubj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlbpqgx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2uyibkvfa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmlbsmnt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecklzpeb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwqnrou.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqoyvmop.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lefzsyee.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2rhztrepc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvzqfghf.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2nnntzmuo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2szfwmfld.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzpxbdl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gxdvakku.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcjyalf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcbdgoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uwkyecif.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbveenia.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxdlrrrx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgbiwpj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gamywagl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bptrqmpu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrcmsuu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2itvhlyxm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jiegkotv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eozmknbt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ouozkqyb.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vatzlgte.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxcjaaw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wrnmlmhw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrkyndp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qlfbbjgz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzlywtvl.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2isqhxdau.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uywhwrxj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjtluvp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzvtzzqd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjqrcez.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yilrvyvs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gqmxacsc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2doborrbb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2wtauabgp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jaujzjup.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2onbqwsls.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wmerents.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vsdyjads.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqhfrjs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpnppbf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtqpbmn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cdbclnxl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ifqskqnp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2faxulgmy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fydbmfnz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adahebqj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2hvrpsijr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tfdyyolx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nkcpvjal.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsxxoui.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rihlfnwc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvlfpug.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fazpgwpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmegzlcm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnovwck.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2urmuyyin.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgoqpeh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkoqksbx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbcgwjd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2skgztrru.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nipptdco.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfubttfm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2wheykpdb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruiitnku.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2beqwdgyz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrnswln.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qpuzjfqg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qicvixto.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2odcgrtnp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2toyktska.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zauhslgs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sikzbrkv.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tptshgia.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qasolwgl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeovoma.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2febypjmw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tyiqdpgi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkfadrj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pmuqtlao.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsosxjcx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2raluamgu.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsnefvw.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zhclwvwv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzzupnot.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lpibxxnn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2kirmkzmk.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhjgczi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhwkmjl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmcgsoh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqhzkreg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ngkyggvb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrmnfqfo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jeipowqx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxwnbws.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sqzsqbfr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmmvdcv.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2egtvskwk.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmnegvv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuidtyo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgevtaqx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kejwwmpn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2siipcsof.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjyhkwqu.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwyqjgc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjxluwwu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2iahdoyea.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvyuwtx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mqdsrlgx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhuznauy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tkigompn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzgxekax.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nvffyjiw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2llotdnss.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2waklowol.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpcivte.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuyperg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2elokjaoo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxedelg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2opwxfgvv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xhqigxaz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhtglk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bkuhzwto.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2oiedsdgw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhselec.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2flizpsre.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkgnyjl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ovjrninq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zisxjaup.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hyshltou.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrydnzoj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzzrxyw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mjznrumm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwdggjs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izgpkihp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rejmoike.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nwstdkob.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omtzwaab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2beyqdmiq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nnyqxkxj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2irmggqax.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avyaeeql.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2idlxqyay.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tghqhyns.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtahoyux.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfivinmf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oasixqzd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ihttokxd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ahalvzmt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypabvnar.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xohrklyq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrdwqhp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2joyieuff.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dtgmkgms.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yiffceda.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvypgnhj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vfydvgug.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2nklfzkdq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2echwwyny.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrireyu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkopcnc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nofqqbzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eerpolnz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdnnsjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lukkiptn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjguvgm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gvnvporr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2canamukm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yodzumoq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mndfccti.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2bbnsvmwu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2skkfvulm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xrdhgedd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmcbpvz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkpdibh.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsqxttr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gnifldga.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfrhgtc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkoxnvu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2acwacrvb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2tiauwnsu.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lflwjihb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrutmqwn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwjcdhs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkhfyyz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2afccovyg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2woispead.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsombvp.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2abghnttn.html


<!-- 参考信息 -->