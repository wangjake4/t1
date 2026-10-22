代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2khceyxrw.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2dzarrkuj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2emalhzcq.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2uqitoluk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2jetrhycn.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2clhdajmm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wpliuteo.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jfukmnhe.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2amtmkrfb.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2uzthvcqd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2shrjuato.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnvchae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2btrflmvm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqtxfht.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2tpxqsswa.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2pezyvsew.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2relhuthh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2uusvmsat.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ewtcgbyk.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2vggjoarl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2onpgjaec.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2rxxvqixu.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tqrsncvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dylcbiil.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2htoajvjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uspfxufn.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdbvgug.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2xnczqwjp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhteryjk.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2jormcrgf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkdqajv.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2suhhrzuy.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgyjqlh.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgpuoks.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuuyzqm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2zinshzyn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuqbxwm.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2hvxcurtb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2piscdijn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bginvzys.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2izmxxlen.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsstwdx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2buwjhgtl.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gsszpjge.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2cdicnlpa.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkkltfj.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2xneoxwcn.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiqbstj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2redfyvbc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2widgnqpi.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlipavig.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpoqztr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uwqsbtuu.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pelbccjx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ziuubgvv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hakwpxri.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mvvinjrf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ynwxljcc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2awgznirf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qlbqfpej.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tekawjdg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zbjsvznb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xndoqpmq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2puknmjez.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkmaylt.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2orbdvipk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tctkrscg.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdypex.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2enwpzgak.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwbtwjt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2bcjeerka.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbfdjcc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgbjyvjv.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2sohffpoo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdelowj.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsbohpj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwizzqn.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kubpponi.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2flkvmzsi.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nohinuli.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2inajmhwm.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcfxmdr.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpblkoe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtnfmrv.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlfatzc.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xizmhpmj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvvyyys.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yscaqgsz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uisujoyu.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lnpiwxlh.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2yowxksbi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qhrtcxgy.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjnbaxx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zycaaaze.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pqnxlyii.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2pduvokkb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2emoxgqlj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2rknosbrr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzqquzp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlcjfngh.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwyfilb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlufkmoy.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2syvsuvbh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtprcfrd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2wigyadxm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jddsbjwm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dllunith.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jloitigk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbcdrdu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lqxqhnzl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gzntuirq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jiukgluf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dssirkgr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hgybpjea.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wndqpzhx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfyiksx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fldsorcf.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2retdfhqs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2cppbnkuw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfamxnpy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ffethrkp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2zymnzlpd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2amvnlxmc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvaslnmu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ladfobks.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otixebpk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbuaauau.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2alydttyt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwukqbpy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kpmrxppo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jcogzyvw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2avcijvfl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pevehepn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eerfhnul.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pilmsmui.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pixbhpdu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eltdoaqw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtewuse.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnizrkrm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oojcmkfv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazoojfr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zligpxvn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2virfkkcp.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2onddddoj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyenofsg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2umprjepz.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpkoeqa.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2smbpkvoo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnqwimj.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zkqewtce.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpchina.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fsqgbnli.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfbynia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xdozdipj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrdqish.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfihpwsh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kvsgioue.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbhgwgp.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhkexee.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xruujwqq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxlyxs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmoclip.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nryynbjo.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pypuhmzm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qaehmbjk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dszlbbgn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2llrdepgq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzncxdl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnckeat.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeuuwwd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhddukn.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zinrbgit.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wppjxrox.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmxciwx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqhuslg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvuuhyg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gmtdcelt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2icfzucrr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rvqhioys.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibpckaze.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qjjwtfzn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uodbyvwj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjwumgc.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2edigbpjk.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjgxrnf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggpkttnx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owhhikzh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qgcdglih.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2spmkitky.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2djikqoic.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2trfgjzya.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2unnwdjtr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zapbjapi.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhtacgo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2twfffrvb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2holuohcf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjuyojkg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tiautfmt.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ldcutcyn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgwiabw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jboezxxm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2elprrgdp.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2buboqaff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqqizfjg.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vuszpyay.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmboyvcr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hgqljjxu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvilcgb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oghtqmfx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcffqcf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jilpvsps.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2llzfgblz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2iclsuvza.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrfngex.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvtdeur.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpvurip.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bsarkcsn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ezqhomvv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oezevkft.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsqdjsz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnypwwa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyttrcf.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmhgkxo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mifkxgqv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kevyzbag.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhdjfxm.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqsyrcx.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iejwsdww.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqmmnfy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbtexxx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2susovvcu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2srlumosh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xkuynxak.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cyraxzlx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvfvuax.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2wqaplddx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aullrjcs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aoajlvff.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lpaxlcpq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2szcadbvb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bsegzvax.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2toargxrh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ubsbmtrq.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icouykkf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kmclnpqw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqsjvpph.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2faekaylz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jokyqgvo.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zitqwkdx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2misanzxh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmptsjw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mudbqldy.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sflcupit.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmxczwst.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmhjcea.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qriykwub.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrohyiz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cmltvuuo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zicuejvs.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndscbsmp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzfgrqu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cbhtgpgr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ylnnngsr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbmxrgz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyktqwgx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsoiplo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2omnldtvl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mlghqtyz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2boapuvqx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tkgldmak.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkegpseg.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wscyzktg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2btybbnxp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2namzofrd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2imnjadxt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2riikqwck.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ododutgw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flcqjlpu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zraqjwql.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwiprns.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2islgpzvu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tysvccch.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tlbftemy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gfjczlxl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jtivyvjo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sipcrzxs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2gltuhane.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2dcedfhfs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkperdx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtybtyox.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjixibw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2svkfrzhg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfywdzh.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jypcrrmf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2irdsbyps.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrccntd.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2meapecbt.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2qvoaebzo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2downabvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pakvuacs.html


<!-- 参考信息 -->