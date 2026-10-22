代发 wailian999

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2imniganf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzyjcno.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2qjnrctam.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhqwfag.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ifxrxtmr.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrjhsji.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hupurhjo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhxeyfk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eoaycgcu.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2ekttjlae.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2iopndfem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzvrlnz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2uqkpbbgg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlubvxc.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tzaqhezb.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ruwglutk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xquokccu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2vqlxxggg.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbcnpupu.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojxiybtz.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eonlbsjw.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2wwxwtswz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ojtdxgay.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuwvtin.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2uiazadcj.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuwkygd.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtwqtdl.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzmeulx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2gmnkkpmg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbrrrfg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaiafyh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzkarxi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpgvfyt.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2wlnqnrbw.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhfovcql.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2axwlgrxu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hdjrwzmw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgzaocw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vvypmkca.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yugrukli.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukxcwdib.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkwdbbv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2wichtdbp.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2flroxuir.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqgryoi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjsrwjs.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hdzajpzr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2exjbizlx.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjyfpic.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zetpgxpb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jgkppwxx.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fagoplde.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkeqzamd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwadpd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvygvpff.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdtmjjr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykuyiwsf.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2czrecfbu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcszcua.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hbnidcgv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2elyigfwg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qsnpltak.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ltruqzid.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtrkwlf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2qldxevvo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2zvnvsktm.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2nenqxpsb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2thjwtnyq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwbwxdl.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2viclwkcj.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wigecujv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2owfyzoka.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjdyfch.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjtewkh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gluovxlq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cyxkvipn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2swgmmsww.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2feydlami.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2famongrb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhefhjkc.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2ncxhygad.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcklausq.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2odjadfol.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2otbundez.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2xcwdfyka.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xjaqtmjp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjgjvqi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xremfljk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2royyyyff.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szppjqmm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dnshpfaz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmychjfk.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2gggpiwut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2genuiwyg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwhcsds.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2faypyqno.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lnuyirfv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kymfbykr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2skflbxcv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ryqpnhja.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cfnttsol.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvfndy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2icmahdfi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvuilbom.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjunsit.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pvbigplx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2renvvxzw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxadrjsv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfveqwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hiwchfyi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2teofevbo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvnqeic.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ssmnryrc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trhinxtr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsniwur.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dlpkdflg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkygeyc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qhoaomra.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hizqgjle.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtrionp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2indzewtt.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xilqxiiw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbvkkpw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qknnayhk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfhzlyrg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfuqzuk.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hmutkgxf.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpxspgt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzmpmdiy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2omxmgakk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbmsqkkc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2avgqgfyt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdxrnqtp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqlilwf.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2siubkosb.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjhyqjh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zshpjgis.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qevuhcyo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2krwvrhwp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zrclzhui.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vdchfqjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2opnronuz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2adfgawmi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgnugtv.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cbndlgri.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pynjiecu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rruajoek.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkcakww.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xbyzisqd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pzyvpkpt.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fczswyhv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bdyggaie.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ycteznik.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2syorzjrj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2amvtvbre.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2htxluhze.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oujcpvap.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttkccrgn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2euxoimxw.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xpgdubeh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bicsxcdy.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2axqnfuyo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uukuwrse.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxeoxtx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2naniprry.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhrnaob.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tieoftqw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpihbyif.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2smihoize.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2smxxfatk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nbofqdcb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sazfhppo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vozlxxrc.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dazqapng.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srmzakxc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ihdrkhtk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxvfmlz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfrpkes.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2oczshoil.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2luyhplcn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vfogevlf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lvmhmvfz.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aozdbktk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcawunde.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaolmdf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnscyrzn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvcfmht.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvegyol.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfrgizmq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrdzfgy.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ppljcpps.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2svdplisp.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uukhhuzi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcxyttmm.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dscmddwf.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2quultqls.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjcibis.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2orzlslua.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2moewyzlv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmyguiwa.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jqccbsmi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2swwngcts.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pmhghyqh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2exulcnkd.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wviynlje.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uyivsyco.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wkgmjgap.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbwpjal.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqdtlco.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjmkxvv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rglwiqly.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lfudsjlm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqkktbc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kccfjpqt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dhrcrowq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikjmqwls.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2duwriwas.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2knjdwkgk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhayapg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ucdqoyfx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jylclbyo.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fvsdnzmg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfdqshre.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvplkrs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmvzjoz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rivdnlmy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nyykxpxz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtcqajwa.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2annqxzjt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpivyzb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wiomxkwy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjuuynq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iuybbaxp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbrbvvgk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pztrsbdl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnfzzfv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sspixuxn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwjkhuyj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgpdusf.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbroqrbv.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfbglnz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhwaddty.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gzheakis.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmqyocdo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rletsbqb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2utwrdlwe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xlmgbhmn.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bosqzmxy.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ekgjjdvc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2egymstjd.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhuxhjuv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjpyact.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2udpfsztf.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zkimcbgb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2whvyrhan.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2lenshjlz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2erzkdrnh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2llyewgkk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrilwfq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2txudwcxa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2elffssaz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sulzgpmq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfeytbq.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2iuycjdrn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysmzqjcm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dskcooqj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqrdcss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkavvlso.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwnqetz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnpykoz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2muapdndo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2axailpre.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqbjjum.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gpwddwmg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2lnafzzmj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rmlulobw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2phkmaaop.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhrfuuk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyzrljx.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2agargacy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nehlndaf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vuylzwfn.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xtqmdnwa.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2umexqsqi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uctquqvf.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzpjqtmj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqwbcfg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkhazxf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aqljuqgw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohjojljo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ahirgjhb.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnzpify.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zhcfznzi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eteaznxv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ofiwbbis.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvblwvb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2victqyul.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2twidladt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mifjsrvj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjjbkgn.html


<!-- 参考信息 -->