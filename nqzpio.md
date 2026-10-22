代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2erzxgdca.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2esoiytfl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2gllqcnux.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eerywndj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsubdyi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2ervbqnar.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bkaxhnmf.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sgspkrpz.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ekikxkfd.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2apdblrek.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fftumcrj.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmkokrgg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdivmtqe.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvohpugi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2otqxeknl.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ycufwnnx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqjnjic.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2tveaoxqd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vkswdrfi.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ubwdoyma.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnudbym.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzufaif.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jtesiwnq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgrlykm.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvigvsf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iulrjyot.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqhdsxp.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsjjwkr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdhcfbc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpsshlj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2lsicicsp.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2qklnajra.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuvbixyb.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bluwximh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2srrntvfp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bwrdxsyi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2huamexai.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yhqhewig.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbjskfr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2apyuurfj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2aztgmdgp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2grmoexhj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2broddmfx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2psakhbxn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2jprojkhj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mcdrsico.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxsrqnva.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uaepunwx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2krlktsbk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycahoujg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zsohjnay.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vozgzzxi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpxewkh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2canabwcr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vhozsqgk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxzwgcz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2rpejwrfo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjufxer.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2khzudbbt.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2olgvqfbz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpwkfol.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwkwhua.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kzllxgpb.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgqmebk.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgeozzyz.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvwksfp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2prlwatze.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vfguyhtm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjspxyz.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2wsddimci.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtfkqsr.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ofevmoas.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypatikjf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2clrjgdik.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ocberrcw.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2htqswqjf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlixblkm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2jjdrzxpc.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmvcsfkc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwzekge.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2olkwvtko.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2azggzrll.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yucgjtxt.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wrozjvne.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjmmjtu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhozhrz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzfaylp.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2lycdveoc.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvrzxnp.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nqwziloc.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2uxznzkpt.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytnnvaxm.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nasxoxjw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbvukmn.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2icmcymnd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqwltrq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgyhfyq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zlkvuezz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pobwvixk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joetxgfd.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2odvfcgmi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvxcojb.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2ctotuqny.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqydjiy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpxezmh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkndorx.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdmlihz.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjhplyk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2byqxsrhq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfalczd.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vjigikdo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ndersfbz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cojaurcp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gnjuakwc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mpojzngq.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jflisxnq.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fbylzieu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mheeyqoh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxncfoe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2izfxrkgb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mgusvwls.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2sandumto.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vaahvkif.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2voqprczu.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2migojerk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrudwzt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xeimcdru.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2isorkcfo.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtxkyoi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvkvhkn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kmzbafor.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ebslagtd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2glvgelvn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mrppbwot.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsobakv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ylngisal.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqqskxeq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhrkuhk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2brnjwwcg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqyrmyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihhianlb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2menbyyxu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2yydjsldv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2icfahsnr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tntkoefk.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uizkukat.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzgwgycq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpvlcor.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyicaeku.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlpsirh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxwfkum.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2orgoqgby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cmaziqub.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwncetj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wydapjls.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmslbro.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbfidnhm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgvzkmqs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2auucrhnf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nsvkowcg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbnznxu.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyasgjf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cprxumoi.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfztdas.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjknqdp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2avgmtxae.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ybimrjup.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2utltbyaq.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjpynaa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2myqoxaxm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hsncjvfz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lrktndlg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynqvvvfz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxktcib.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvyvpuz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2owgqpzbu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hyirsdwr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnmoztm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2raaaxxhb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpguywhd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwtglly.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbmxbzrz.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqrjcgee.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsoaawnu.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lettlluh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkuduvo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrpmwuh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmekgoxa.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbrfxnq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzzgcqj.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sasjlrrp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmfuzpf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cenldatb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2exophcat.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dtklphkw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcssffmh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2prmazjsi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2podxhsup.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2etsbuiyu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eclxwdte.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzzhurq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjkaawu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zzocsqrl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywfipupk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pubptrwp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpnmvhsq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xepipjdn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnsivvj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbjsmran.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtltween.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gywobfey.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpebpviy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvygkjp.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2odkjwydm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2imwttpub.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mofclgnz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbomlhnh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrtxqfu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2goamqfxj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfonfea.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vovxfuli.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2fliiwxvz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmtbshyb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrvrnct.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhftoax.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqoqktk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2spxlnqvd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbeginm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2zhaxkqqw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsskksq.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2esihgwwn.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvwvjde.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sbcdnkhy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxueoguf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyhepcj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ejpctuiq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2klyysqhc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lcciazos.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjllygst.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gssztawi.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvrehqvg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gwpfrgtv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqjdiycy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnawtctl.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xhehrqsc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2deysqekc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vdqiuqrb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvsqxaik.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2apmanyyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnrtpfo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lndbknvi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lolhyuea.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2comenwpp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwxjwzp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkjfphog.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kbudshge.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umnkxoan.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2knnticex.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxjcofrj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quvojmbg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2utqaiojq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ewcsjxms.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsktvxvj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvbtemx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkbihgk.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ntchjmaq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2btztugrn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bhmxgzjw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2plbbacuy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hfarenrc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2chmmsznd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkrashw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ccccfaxn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2semdbieb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgfrkgaa.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpqrnvs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuxvyqm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rpuspkye.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vxbsvixy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eywgqadn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjgqnso.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bcveauyx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfdgqqa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sronxdcr.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2uahxdvks.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zwhbfnsx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2jvmxkvfb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jpcatscd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwxuhsp.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrvkjkm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sebpahsu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2julrrdlc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2grhtjmrc.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrfmwwe.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xfozgiyp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ovgkfpng.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2phsmcdyz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfuwheo.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wshblyqu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsmcggz.html


<!-- 参考信息 -->