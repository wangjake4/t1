代发 wailian999

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2xozdwkqa.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfqsgenk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wqlmvobn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrptwwt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrwbjfw.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjqrpqf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2jcildcrs.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bryfgzja.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2tslhjpok.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2acoowabg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkfepcv.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2slhrhvso.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qvwidevb.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wczhsrvw.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgqlmlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2redprchr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuibqqz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrinyfv.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmoxhzl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2btkkeazd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdudbxu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kskwlsoa.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcdjfha.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2xegboocj.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdivjfa.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrynyzg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2tenlxswt.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ojohkilk.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2oliabhdd.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwbaept.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2btrdfvka.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdkvoug.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2shklhpvv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pgepdnne.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpbucrd.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhlgkzt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjazbnj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2suswcfsr.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bjatgigc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrmzvgp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qqqsxvxm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2aylbhohg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddidimtm.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tmlmxrbu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2kgidnttp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2izbssnuf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmmlvsz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vykbkgdq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqudntg.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hidlnijp.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlfqbzu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsrvlou.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjpaumsv.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ukeuagok.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ahwlxzpx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojqnoihp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2bwazpftp.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fdroxzgt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2puybraji.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2djjeipuu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2epfuvfqc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fbrqxrkf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jymvzsgm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wlsrcvno.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfkyfcm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2wthsulix.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2asolqkxq.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wkncutkv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqvdzlp.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjtnjji.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2zusjkneb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nbjuuyqz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mupmfuoi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iethtyvf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jghqxmjy.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2slobpdbg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfxsjnca.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihgwerrm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbsmjgub.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdbkqly.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnhdtbi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nsshhcbq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cuefyczf.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2croeyjtp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ijkpbbry.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2occwhznl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zinpkuuf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiellzm.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kkqcfyqv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2aaatqsrn.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2qaylkflq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yoajeqjl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgnnyds.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xufkrktz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2myiotrsn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfspgfaj.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsalrnn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnpvrjz.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzsggxiw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dmolchzf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrbwgty.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwlbpis.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zvpsmjly.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2aafqpjhb.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtuwojm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ossafdvd.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vergovcb.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ghamqvtr.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2llpklgac.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2geuhuadt.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2gaobgjjl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpblcmwp.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwhlrwi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2plhxhnmi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kdccdjvv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkvdlich.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnqnxsp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svczsbyk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xacviwer.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2svzdtniv.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzkcgohq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qprbhiqs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpnmcdv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqvnoox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2roknupsu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tylmkjez.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxdruwo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lwoeasgu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blpgrqcb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaqgnup.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbdcsfo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yldrogtc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxzfbpo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2txvdvccu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfqkuro.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pjznngmw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwwhfuao.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fqoxdmgc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpcgxnph.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bezjksgt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2igtrqzrn.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pqakiexn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuafipg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2udwucypg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2efxhygtx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2htvqjicp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2llmnuyuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfmfgvbk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrrfbua.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rezrqewi.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xdfzwnqw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vknotoga.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zdualymi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2weccoeee.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ihefacjf.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2byskwbye.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2werlyqst.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qgkthqmm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tfjthvoh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxlekwz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ihweksms.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfcndhfn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hcuuieyp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdrmlpbm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wqteuwrg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwcznnyb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qhndsnqu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2onctwamd.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbgnqxg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiewjxzq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xamefyhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlarilzg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbuwhkz.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ztvjtabr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pktveoqn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqaxfee.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vmkyyvoi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgsxocp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2epphgvke.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpluspag.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqsdvpi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fteiumhs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aajtadgl.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzhncvi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jjlrjpoj.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqxiqcc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrpiovg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2uaratgrw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lpqfatzc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjrdaic.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xbmjbgxa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqodjui.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uzuqpqfi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2doszuxip.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vxpemcpx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwlijjwk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2afadpssg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnwwuxe.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnkqfou.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2exejluiy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qxbhphgi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sidjrpyy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lqpyadtl.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2goirotby.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2mjpluxii.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmdtajk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2donjclcw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsmhidu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdgxfsz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uryrngxu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwbubku.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2fxsaptgc.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsbjqvx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2awjhkkwi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hwhkrqou.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ruvivitg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ibcxcrmt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oslfweue.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hejxeotk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2sgrqkmng.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrgwgvb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2anoixgjf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cttdtcxj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2igcqlwpj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbfqbii.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2owswflph.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhiwcff.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhzqfpf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vureziko.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sniqqzkg.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2luysidjc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ctxzwsum.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cnquggyd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2isinehij.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqfzmjgr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfomksc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhrqnee.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsnbvljp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgnndgc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvpmqnr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzfytol.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oxatwafq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wovgiaew.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctrwkqst.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2voxosxyi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjvwfzd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2izotycqy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pueiwcfu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwrbkpod.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtsasey.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrjkdsk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jdelftdp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kwdxpamd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2abehvmff.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2smbpnort.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dodvuhdy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhrtwma.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mblwfgis.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2idkcfcow.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2biuvduvf.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjpwjbv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vihlhycx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ecskcisd.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzisxzj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hzdoqozv.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ycftjhrg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxtfwzm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kewwyobn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcndrch.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmxbnge.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rjwaqbtb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvffsuk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbqsueb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tsetvkpi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2cayytpni.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbstctb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpuydby.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zeymukuq.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2inyqhrmb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2drkminhy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwzsjfx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxolhtus.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nkovxulj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dqyezbzy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgyvlub.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xnukcqcg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2orhbobnw.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2agemjnel.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjcoimn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiemmoqi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzovbyz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbjgtul.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mxagbkqa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlupeacz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hiuiyevu.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2btmynxir.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhazbzsn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzmlpafo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbosjea.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2sflzuyqw.html


<!-- 参考信息 -->