代发 wailian999

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpzlycsa.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2snpjinbs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxqbsxs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pztttdlk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsmwhso.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2maiojmhf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpocjqqi.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2ogcgxuql.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ycbwkeiz.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2pibkblif.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2yppcospe.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2biecqotd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eyfouabr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnenpnrw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2blolksrq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmtmkfm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxigsbpi.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ndndqsku.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzeoeze.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2smvzvmro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqwsrue.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwnfngk.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gpeudzrd.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2hqyzrifs.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbzwibld.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2iscpenbi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpmntyf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2quctqdso.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2nydcsvbj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lgftyhvi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vgpuoyoo.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvoucxk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwqhnvj.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2dxeizezv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmqwtwef.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2pkjcvedo.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmosavlq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhecdawj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhuyyke.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrdjpuv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ekbtrdhm.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2faugxzfu.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2sqlzoqaj.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2djrpbpag.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnygtjld.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2qzkzxlgs.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cksbmqqz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcggwiak.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2czoqbdbe.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pucbtqbm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2gujxpmph.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2emdrtetr.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwzeind.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lmjosahj.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuwpviu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbefwmk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlhqhpi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcrhcfe.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwsxuxe.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2edeszvlp.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2onzfaklo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2kahlgpqr.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gabfhpze.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgavhajy.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbxdgry.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bswjrlea.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgyzqxs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kishcvyy.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2flxfzyap.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2txwhjnjk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ulnnczen.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2aadjatjp.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2meywzdhr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wqiqmmtu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gthcqhgq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2yfsbsysg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtescppb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wfznoryo.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2heydxxlg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zgiqofly.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mxniaqpd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpqfujp.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mlauxoyp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmhmsry.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gkokrzpd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2urrzqfjb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rughgfob.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcyaldxa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vttxwyfc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2avivoypp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvcpeyl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cesvkkzd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnzweylt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fesqlyie.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2biwsgrxz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpnyexp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2szujwxaz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlnsaqg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kgaxiaan.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2nzawwhxq.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2khmxjgvf.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgpztir.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqmxijc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qvzkxtrx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpxzaqa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2auemmwll.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2luktwlqx.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wczevhvr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jamqxnnq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnruihqa.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vygcmuhy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2atitobzi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfznguvi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2geufqgag.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ldztfljz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pshzkpcs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2yffqlzyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmekjui.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2tyhsnqye.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fvwcqqrj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xjeibjdc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ystbombn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hizdmste.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2awjwyedo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2svohshof.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajwanbwj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gwlpujdm.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jrupqzqn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vohebblj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2euckrhsh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kqehxxze.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvgjdrp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfsfrox.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqwiwaa.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbnzgwj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsckrnka.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iakyxnjf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzdrdta.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dwaubvzz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxrberr.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fhehrbhy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uhljherr.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ubiazgfl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyoqrpv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2chtjkxly.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdvfrhq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2neslxxjq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bddfwhea.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jfrskwaa.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2taagmdbx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gojtuead.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2becqhadj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dshpsojz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2etafcsnp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pevtzgcq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wfiwzlyk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ydetgfop.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnyllwo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cnhnuxrp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwdnhvkt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vqujwzfw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxxlaes.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yxjubkoo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2povlsziq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2givcxsvf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbkwmkn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzrwolw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rriwmran.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jloqmfuf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2enopmflq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rvwxmjeu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgmjuok.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bfyziygj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydtxhvoh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2czotogfx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjhvlbh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fkfaydcn.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvdxouc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zyrngrlh.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfbtzmqx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cylcfqmy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdaysser.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgglsks.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2cncrbtne.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2lebckkgt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtzaxtl.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2opzxwtvt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uozqqvcm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2salolsad.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlwqcfi.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzwaecf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2idfixcoh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfpbmuq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2psbebfif.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzbgsps.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2grkrffyb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvfmeqzh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2objvzhry.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqijgjy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2twfdbepf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lczwtkqx.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ciguirsh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ksewnjsf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjljtkw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mhvsxftn.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjmzzudn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdbghvp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pzbgcmbf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dnurvpzs.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipcxqbdb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfoewyc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivdwfhlx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2clpkpedj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzbisue.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qdfhcfni.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsdwwal.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luedkgzw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmevcasn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqvdate.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2opxrnrtw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjhmvsac.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iuwwqrex.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chzitinq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgpfgayf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2piscfzkd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tylzhwhk.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjorrgz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pffwqhtn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmobqtiv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wpffmyou.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvcsxukr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmcyxxb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmcegou.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2npbeyknr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aaiplrxm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uzpbgsgc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2mdxvmieh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mwilffwo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyzevpu.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aomzvzix.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2arfbspor.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imalnpun.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpdfnwpq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2txjpqbbc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wdctzpwa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pznoddub.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxhqrmq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnputil.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdasiav.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsjcvga.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nweqblcr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyajyvd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrhibhk.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2actuijgr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xntmmxdc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2oypbjzas.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mftaowes.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyhqzixl.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2euxkxwcp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rgtyfvhe.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sagdzvnp.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhoxybz.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zhclydac.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxuvnwg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2otvpskds.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iiazshbi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oytyqdpi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxnypwh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ocnaktjs.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfmesrz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zzcuiczl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyjhefnx.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lfenoxod.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2corwdauh.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2jfabcfgy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wpynilzz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzffhcb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxsrkhop.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gzdyoxgy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tnslhfqj.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cqpmfzpe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjbhzxvq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzjbliz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfokohdv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2dcaruplv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdxfvmm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sjdxogfe.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wctfqrlj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsuftip.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eredsder.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hravpuvn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhxdvcnj.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlrksfz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rklienzd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fsylegzl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlvqgkt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwyivwn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxaxwmc.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fcffmkew.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wejkvvgr.html


<!-- 参考信息 -->