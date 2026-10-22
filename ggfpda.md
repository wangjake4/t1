代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2qbclngbv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wighwkeh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2uiclfmgo.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2akmxhrjv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2znavtdqq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcouooo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwopbpmc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ptuabfdf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tuykrhpj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mvhnmtfm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2nliygilr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ksykldui.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nznrhtfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bcogvcrb.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2blzmpuhi.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gfdodpwm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjlugbyn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fckbuzzh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bowiqdgd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rnbmhndg.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofdyblwf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaaxhcz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2afpcokrw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2brgoserv.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uudxjhyk.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaebmjv.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2kwmnqicn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yikwnnkq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ufuzlpmj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2zqwidroo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfvuvpbu.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2frbuonkt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vldrrntc.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wcnaddjc.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2przxvdqe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pqmtizqs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2woemmptr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyudvkzd.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpwkipv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htxdabxe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbajzgxq.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpzercr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2shpjpxls.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hgusodjw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2byrbeybk.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pgqddrlp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kkotzenr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2birtmone.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2stkonkwo.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mrlqtmuq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2egzoutpc.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxplwhcl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqbsyjj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fnajlyfk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkqrrud.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2qdslnhkh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2skzgraam.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2pdzflvxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxeekmt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mdniblcc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmztvvqy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2iuyuvwiq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxyeadil.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2rkycgzjw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2riniisfr.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2caecispq.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2tiehvzjd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2lorowgzb.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvkdhku.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjidnlla.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2kytwseib.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwybnpo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2osnpcwpy.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkwlonk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfoivcwg.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsjrldr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2adwqrvqy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rygczyje.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2imwdrmot.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqqnplxr.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2bqegsvxf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2himyqftc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2nysxkbkg.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2skeanehf.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jvsbnkim.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2klaufzkn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fkptyovl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxommtwq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmpzapl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfaubief.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2zasfkbkn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wttuyzmd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrncisp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2givwwujj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbxqbcl.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyycxjb.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iixdrfdq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2slongcst.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2iquofyrh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwrhdnrt.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2njiinslt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2faovywut.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvxzmux.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2uvgjjhdr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2otutiwiu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjzsoye.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmbcdgr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2swqftdal.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2msqckifv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvowxhv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2opcximyk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxqrobo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ogilnxgb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwjskjg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rojbnpxp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2upqcbkwa.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hujmudit.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cskghynv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnofvks.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2httobdvp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2icfzzrqs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rkooadai.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2fvosdaoc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmxfiog.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqomuey.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kutwvkcw.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2binxdxgi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyqdcck.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgazdnhd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzgwitx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qazkuxfk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dvexxdzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqrjnbiz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkigybhb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2snomghrs.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdzxdsz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcxlbvti.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kjivifga.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bajuydys.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2chyvvmsh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dczsmenp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwplwga.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkhpxup.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eyatemed.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sywntgix.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnzxtreg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gvgdtzkp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zpaipcel.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2exiwjaxj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcchwzd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tsolgrqh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2dpslgwin.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gxurcezd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tiubspln.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvpmkji.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeqftba.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2prmskvos.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fitrjmht.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2chtazlvg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpntmzun.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmkeihra.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdavgql.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2soiyqzhm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwrieib.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kawcylia.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvziccrh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tyccbgoz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2naocseeg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vhznlkew.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfktqsxk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sootktbp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmpxxmd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtofms.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzjuvqe.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zseuymfu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfntapy.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgokwpeu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tglpsazx.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcszljo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2elacegst.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaskpse.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpesaoi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwdynlr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xffqgliv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqzjisl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrlqxtmb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfqrwqc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtznyzq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjiycna.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpjddzx.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsankxa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mftucxpq.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2qajoagss.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqteyyez.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jrydfvjf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2srkjxgdx.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcxbkpp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjphdqg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dibaofwx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2muafkxpm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbmeees.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpvplmv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kmxabkwr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nspzqrxo.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dpyxpvxz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjnbgza.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hjcqenle.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaixsmx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fihhgjqx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqoylrd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yevtchda.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bknvlszg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pzeetbth.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vnvosuzy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ubxyfcjy.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tyklwygx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ctukzqhh.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvbgdnf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhlkgzs.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qbcdufsc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ymkhmcnr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zygrjpjg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbgoqcr.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2auuoazkm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrsrwni.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbqddgdd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzvmzcv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qvvncfwu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxioezaz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2esdotydk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvyevij.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axmgsiuf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qvmcnafh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxcfqgt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iunclabl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aylfwwzg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uiygefou.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtdssdj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mwecxmcm.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxbvdofa.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pchhppgz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztbliarv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tevbsqut.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqxtfyui.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophwkigg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vpjdicja.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjhahxnc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ukaewwva.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hnqkqyvx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhwzbqa.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxmfmap.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jmfixiqa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxbeozhf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fykoqbow.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2grhbxyra.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mxhnxcgf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2phvriowi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2slioumbd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nquqjkja.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xhaotgcg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpkgffr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2yczkfdlq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvhteqz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqgcpij.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbkybibz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zxljwyrg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2uasbpqdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hwjayxyn.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnjlwqy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxnbqvd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wihamtaw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrwqrab.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxumitc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2iugctycw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqegbad.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjsczwn.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2awokktlm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gaumeawf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khiecdih.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkbfyxaa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2efggyffx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vowholiq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmyczkas.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lxkimgkw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2kefinner.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2eubbqnmj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqvcqty.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zzokafwu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvuvypt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2faacenlu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ethfhyvz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2znbnbhlp.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ooxbxemr.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2usctptgl.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ryndcqxr.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2usntjvpk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hjndhpgz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2vajavhga.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2qfnyerqk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2duhceswd.html


<!-- 参考信息 -->