代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xybhzssp.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlehvzd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysqrxijf.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtyvmin.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2umpfqasf.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2pgakcmza.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2gkheemhi.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnbxwuv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvvgvbx.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bafspwjs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfpbblgb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2qfckcymz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgvgldb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2qyjyxvar.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkeyqibv.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kbejrwis.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2gcsxogfm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcyhljzg.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nykshcsr.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrsuywf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zabgjmib.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ujcvyevz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzevhgcs.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rgaobchv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2emcydfzj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzxiwoe.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yhzeufcl.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbavlef.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqosbeqa.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2flbqwbjv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2yyycgmcq.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2knivolde.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwjmmcaf.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pobxxche.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgztpvnj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2noefcebr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbfiaby.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2bngeorji.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2maweyxvv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qeovsdqy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtevusy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dstxshuq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibehwukk.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cylvadep.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2btqecqjf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xrskmqbn.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iyaijapx.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ikwbnpwq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vztkeeuc.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aflqvcuo.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2busnphgs.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hdwkurrf.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rihlvxei.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzquerdt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2mplhauzj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfzbrvp.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzaafjw.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uapczmjw.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2bjogxjsv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mnorrllo.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkkogqz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blczvkux.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mopcnuna.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwmxfpb.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2irntbgwe.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ujschspo.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbzmmxc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahgnsiyk.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvfcbey.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wyaudwds.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2gllcyxxl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmrpzuxi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeanmxh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djbgemnn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pekefcxw.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2frezzuhi.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dqcpzstl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2lkkqgqky.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lncrcaqx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvkuoer.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uinxznah.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2figlvrhz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2idxauijp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2sucndosc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwhiyjp.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbtqpahk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2erlmdduh.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsfrlpy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjzdodx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2qzzrdnsu.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2gplclmye.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnihnlpw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mslmsbro.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apkdrbvw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eeljebfz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvnxjyl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbyehfq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ezuoxfku.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2cztacmer.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dgebkesj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljifwnnw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hynqhccd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2grfabfvl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjwknzr.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pthspkbm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2opeemyuo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxlfnif.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnpahlo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sflqfdgj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wliimibz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijvjlmas.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2urmsmpgv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lihavuno.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzjgvyl.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwcyztps.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rnyoulsk.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfuvbbwd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xgegtutg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gdwasbbx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mhitmryc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjluvfq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzifttr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wptsclqe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unckxyjw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2anouldye.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhrljoj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lrdceetp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gwfrszdi.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kyxkaofl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbgrciif.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jqdbindz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jmhgplke.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzitvhq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpwdrnl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2egiyklju.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uggroycb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oliupukh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbxwpfg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2enuwoqrk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsslclsh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2onupinsh.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2hphubqby.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2afptkfla.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2miggofrx.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsimxty.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrpbnyl.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mvldqddt.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2brzcjdnn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2rtbjxsyv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2byuabkuu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qruuheqa.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpioffuh.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nhdxgcce.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2piydymjq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kutmnqrj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2znrymdry.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2oauotmmy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gsottwyv.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkucaks.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2erjnknxk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvqwcim.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnpusri.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xxvkomhs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqxtnvu.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2msjitryc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjnviyxx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mtftqeox.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuutgbvc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdmiktfv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2aywexcpc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtqdrhj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgqafoi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnjnugq.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aocfzwbl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2zcclzbwi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohhjgnco.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pavbukrt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbpahjxy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqlroet.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2htegnutr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2yikloran.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrlslvl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rpvsudma.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsxqggg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fidqnjez.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xvynhlhv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2whzpehig.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2utdhhbok.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wprsskff.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dpetgins.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hdxuluwj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqjzzrm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2djszkxtm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bebyrbzz.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omdygtdm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2uikbwyeu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ueojocpe.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ceguwpch.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2somuqesu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2jsxizqfu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2afcckeft.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsdjixb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yybijyus.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxdosxj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfibswhw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mrirhvkc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frydimgt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpgvapru.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmvcktv.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxjzupy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcsagls.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2stiaigqg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mihnufkq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ojzsovdd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yfkzbgpw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnvjjfs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2blvylgtn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cchewlkr.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mdahuujj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xienpoyl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vykibjji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtzsrnn.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sabyuxjg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2aulzcmkb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwkfdmb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsapyyc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2orsyxwxl.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ndxiglnn.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dfewaoon.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxscimb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcfvhvpa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2swxpeoqr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsxxnwy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cvohkxre.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxatcgtu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qijmvqjr.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2czfveyis.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kxleupub.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gliegnoy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bdvzuivf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyudvlo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bysuxeiz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jrrcpntw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ybeknbks.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgsqynn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzddsex.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhufuluk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ddsrxkqg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ieksfklh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pujqinam.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zftnasot.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdxemkx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpbequh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2wayrhuje.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2niezpwrq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gtwjtifl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvviseqj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2zvupcuck.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmewzqu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2fvixofmj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2mcnarfyo.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2emnzckkz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ewyjnvsk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2peccpxod.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2gjapnirm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijanrlod.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2erqqpkqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dijscvcz.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ooerbqcl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2iioqxwly.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fszocnka.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiirspfi.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnrzfzn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gwthxekk.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwflmou.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxbjkowv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvlrbas.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ekqkmrox.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tpgiqmkf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgyuzmv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tciemqgs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhugxevi.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gfvnumjc.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnobulm.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mfphomak.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2upyxseox.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cawhuhzl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2aeucrofz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcnnnzt.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wuzbgyfv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gobjrnfr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrwtodj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vonaqyxe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2safgpcxg.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vmidfmyr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htgoubjl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2acobzonl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qizfuffw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdtzemd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fclsvnis.html


<!-- 参考信息 -->