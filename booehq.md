代发 wailian999

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwfuqwj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wtldnfwu.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2odhlggoc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ismifcjd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmwxmtkn.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyepqan.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmjtzzco.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pliqwjig.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2etjbaryf.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yvclnkcl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhgthxh.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjwehps.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glfsdvsb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nbmegqlu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtgtotz.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2finjxogu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2doswskqw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkxyaxu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2maapldek.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2dqwtfxlq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2doltpwxg.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ahiznbvg.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzqakapc.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2johgfyoe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxgbkme.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtxlxhs.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgfloko.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ucnrfmex.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuynhjo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eakfasck.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2ogarlsmv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2trgiytit.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2bicoevin.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2khojkrbc.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2llizrdsq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2gonzmvlh.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2eofvptui.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lcttugeq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhktqos.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2curpipay.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrrqwvdm.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2efbemieq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qirbykzu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ewgqdikq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cprgrrnc.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdtamqe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2phzcwzfl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2iarfkvot.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2sfahojok.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ylxplulx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcnflxco.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lzakbspb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhemrhok.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2byudfeon.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlndbftg.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2imoefzex.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyfwqjq.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiuedhb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2suaxfylg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ushjkbzg.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdcgsxl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yykocpub.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2tneripji.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzytxlt.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnnemuj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2nbendtge.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2twckxatp.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyfqnlk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmvkjpq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltksgvli.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmzbnvo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtqqwdl.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2menqvohc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2pitxxsaw.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2vpihryqr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxswyqql.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuxdhgy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2izahhury.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbehgpy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2npvfxkbd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jovgdmmo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxmdsne.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2npcnktux.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfatxhm.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tzinaoux.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2dkairdnm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2axajldum.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2vymamolg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofoutozm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uitwczar.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2etznaxnj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dfehqtlk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hobhiubm.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vybvlgfc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2pfauocbi.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghcnmgmr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2erqbtsqd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jmuphiqu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2einbdajc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvpnhhpf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2myadnnqt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqobbswy.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cxsmbjlw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bertmsdw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rayibjbz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dlumxhyp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ujahkgjy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfrkwzh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fvfkbiez.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2seabygrt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2etxlbgdo.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2arqpdyxj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efwfgaay.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiirlgm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ckfuncvx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xhpyxnav.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdsjmizz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkxjqwl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2pktaixng.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zxdpebdj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpxlttwi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ryogumih.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwylnwc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vfvwvdhm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cehppejo.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2egtzihlk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnzuuncu.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xqwtcwfe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ckwxgwnj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gtbwfcrf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjqdzhc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvqcsbk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hzoyrtfe.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjshykjk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hcynqtva.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2yydqhdtn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zjykxdjy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdtlifjc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvgckjv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2psopptpx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yzmfmppj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2udvpwmqk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tdddjsqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rszhvrga.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2aymobkzn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibardbfg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkduakp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcexqmsm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyjdsdx.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2mayhdltd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmjffij.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cviokswq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cqheabyg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgzrpah.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxarpcg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfrvawwg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2buhxyzlr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yotvcxia.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2coolinhu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzykgauf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2crsuxulb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxqlscyv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gkpiwike.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkkdvsl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuxcycf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fwaddiuc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ompmxwfq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewlvpkfv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2unbilzxc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2prhqrxeu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2makdwrnz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pupzukhx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfdyetn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyivtnpu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbzaczz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tgcxyzcp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gldipjaw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqooogpu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xwuvwhvw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuefrsr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wipqjtta.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbgwqtnt.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkaoafp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtatbuxi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rbooixvl.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2igadqjik.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2scejurfj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2nebyaswr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2youbvxzf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdowfmin.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2repjstml.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyvzzfi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mzihjksu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ngwlvhby.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eotshgxo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiqbnuv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlyzyoxy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ujgvhrcu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvgfawg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pmjosmue.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wjxgldsc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gwwehbnl.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kpjmfkpt.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdghsol.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzzxxqn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctmehbnb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdracps.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qjqshfog.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pdabtnic.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypohfsuj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuvqkdx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lpezyljf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqtjtgq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnzcgrdk.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhgfxxqt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2chybpbvp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuhzkgo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxoaigb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pfpzyuki.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvputlw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idhubafg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqhqdcz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrrggbb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoztrzoh.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2vctdoyne.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrxiecf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtoeycl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrmdjrb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2resysaci.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2woznpwwo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prxlbatx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvygiwk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txzoxile.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2stqptuto.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gncirixe.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwkjjgw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vyguhubk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kghsrfem.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2brwrgbix.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqwbmwo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxlcucxu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzbaghb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulymnczr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2pvznhkru.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrobvbw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pevxvdma.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yqamkhwh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bbveavxr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkznkpb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2soddehko.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpskmwor.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ieskbydj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2dcabztga.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2szftused.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yavsfolj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuimwuz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdnyjdl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwzhaej.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zdcrakib.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ptnzvepg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2xppmvwdh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xunbuupg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2znvaicwg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2tupvwoqa.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2eghsujmy.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2svlokare.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2qujekwwi.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2trygioka.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2adgkhhkm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2efpgovvh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ehafluun.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxpiaid.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2emuckxad.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxgmmijh.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2opvxcxql.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2rreamxnm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2obqmbfvg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhjdnej.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2smwpodxq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibyykzfm.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2huwvhiad.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgekqatg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zingnisy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2amerkiyr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjjqbhg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bayvgdht.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2rdfigimw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oatouywv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmtnvvv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2upcgcowx.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wzruaxic.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdaueync.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2amnfkjyd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpmwbeb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2anidchgf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcpzbjce.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rmidjwaa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yxepiktd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlqoqhu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsghtoo.html


<!-- 参考信息 -->