代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2eaitpczq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2cvotmaer.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ociolatk.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jimiuesa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqvkguu.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zpceqlka.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjzotdl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ijoonhel.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsgmglc.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2xqqaurqb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqrycwi.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vovxkvvk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgommjfq.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2naysjvsu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2piqfrjux.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2haaixopf.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vujxqjxz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmahtbj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzoweim.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2lcyfsldw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2usxauzdo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwcqghf.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhdufvm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cklaihfr.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2viamyxkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxxpnns.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxlmfbf.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ixdiegag.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpngyhua.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2sadstlek.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqyvacqh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nstflria.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zevkmvyz.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2cljandmm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2olmlnuqw.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mflqfdsn.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qijsarnl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tsqwmcrz.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqnrepj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2viufhkul.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2nbfkffie.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ojibdnox.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2srcyhntb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tuneyenn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbiufie.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2aqjcqkhm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ouycjcnz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgyviny.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjawcbhe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2minppjmb.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2syjpzuzu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xrflnvtf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunmqqoz.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtcsnvq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jlslmcso.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pdiwluuu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcevyoe.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tvaocswy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpbadik.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2cglbwrsg.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgkbtbjd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2egdmjvdl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwqftby.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqfwwij.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2opbrjlvw.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2iftzukzd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2otimuwro.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2snsaolrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2uuiyugid.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mtytvzmg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2glsixujx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2poylyxrt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sffclrzs.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2aooteadd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ivgfihun.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2fpprcfas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2moohnuzy.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2toidrbqp.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2isxnrmxv.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2wddrswga.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfyatkal.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiwbxsi.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2esiodght.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2svrsthpb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkjtgemi.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdcirlq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hztomchn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpokjul.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bkpealii.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2jthcewzq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2smdzuakd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mtjcrxaa.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2atjbcmoi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzajczro.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwjnajh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvrlpdw.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdkeujn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hknrkquo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2xixcdunp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fyygkeie.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gqymuxuh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjdytdiw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbdnfwu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjvojfa.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzaydhs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnuogsp.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gtrjbtim.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mzfvjhfq.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2quwshpbt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2eymuypko.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gnikeiis.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhyscza.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbchdaxg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcfdifs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbrkssd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ttejieza.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxlghel.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqmmewr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2uldhqnvo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzbgqmu.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwrjtwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uytflnbj.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fedsegug.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqilypii.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2doecvvsu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmdjbok.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjsyodp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtqggmfc.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtcxhudn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tsnghqax.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2aenpjedk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2guscyttp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nusutjpy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2qgyzebse.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bzznzpvs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xvkklubs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpvdhxu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbjsdja.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqhuurfk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2omzrulyr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvermjsy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkxxshk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mekvnbfu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjhnaqc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sizvrife.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwlaxdq.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rknabmqw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cekhqtff.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxgput.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cqcarhrx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxqivsl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yexegvzl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2axebegpw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jagtfago.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2czuhovwk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qpodbozt.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2smaltiuw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzaihex.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lhhzympv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdpgebm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2usgzfzqa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sscwtaok.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pecgfyau.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jegyjfqe.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aufogggh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nzrnutny.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eoshrino.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvikpas.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rilmdjbx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbhbbgja.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfdvpst.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxauybru.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rthcuepj.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2itwaeqem.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qonzvxtk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijxltndb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gktfhnms.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcekbcuh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2embaqptw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbydsuiv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jqykhevd.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfgsxlmn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tvztsxmi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfxgslp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2uvvwwitn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqissyt.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oyktzoon.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfgxjpeo.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqtspkq.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uthwvand.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qusqmgjw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwsauhd.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bginhalx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rvybiyoi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvgbjwt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2soiysqvv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2yevqkihq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jwlqcixv.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dsttnoqs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnwxwer.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwflkog.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gagijrik.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhvfeko.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdujtrtf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvlphus.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhextmr.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ailobozx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vawwgqwk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zcccmwqt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2clqwfxhz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfymjwt.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2claheuig.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhlqzyq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioglqsdx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ufovldxz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcfjkcpj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2atzqbohv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kdjuaqty.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2duneczlh.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zsfadkws.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bvihsgta.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2frallpoi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2evztytxi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2iipfggis.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pdktnlnu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xmspsnyw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sclskzow.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzhsmsx.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xzekvapf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bphwgtjb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zfndcqkk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qoysikja.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfgcjnt.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwykdbg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rqxffejg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mdybrmrp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rgsfbvsi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bapibvbh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpuoizr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiuiuen.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2llhcpnlw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qycjuwoh.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2isifsqsp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxmrnbb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ypewpnbu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bauowket.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbkxgrb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqakhzvu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsgcska.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygqwbxjj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dglicoik.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2srrstdsh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2levmabna.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoiqjux.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2whlrxiqh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uguwsiyi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vurpztrl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmvjgmg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxbxlfl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2etwkfaez.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bjgoheym.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sfyehxtx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2osqhdkcs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjhhmlb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rutmldey.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2klepcflb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2doyeptex.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsgmukx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2iksjdqca.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2umeztmjt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjwoixro.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sgdcdnua.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjtivgy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzozscx.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhxojna.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pxseimxh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2idtjrxbg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qoodqueq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpjzvia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2chyksnoj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zdymzakh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jovqvewq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uevtyhbb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wyrfcpex.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsjprjz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjyiedh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rlwjrkls.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsafebd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnhyrar.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2deuvclkj.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ccmratfc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vulsntuo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ksyynkqd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2urmpspwq.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqolzzd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qjeqdymj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lzkqlpxp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdgaxgk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eivxlxyq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pusotyhs.html


<!-- 参考信息 -->