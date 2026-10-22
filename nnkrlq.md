代发 wailian999

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhwdqmg.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlgdxqs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsnjbgu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inanhqay.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dexzqlgq.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2oouczyja.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2jxyfwmvr.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtzevdz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2bzoxbbif.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfbelji.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yymqayew.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2bhrbhwhu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ggixghqj.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2clewmmut.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvueprph.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfwguel.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrlqnqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfymwisz.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuwdopn.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2umtzvlph.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxxigcm.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2olmbohol.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2iqjsbjup.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xquwmqyn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdghlpb.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aypgotpl.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2htwadbor.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuihgld.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lnwwjwsd.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxsuarp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2mqwdjvbd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tovjqgcn.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqpfxph.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pobruxpv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2idlypvfi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2nbbulrgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2dtehzztw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgcjwct.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2idnlgxnf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2afunkyet.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xomjrsgm.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2dndlbajq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2yugoyalx.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tslanuwo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmydvgky.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sgyyujqh.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrkprgo.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfhbjob.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qslwkcdx.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxbpqnq.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaovtopz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quofyomz.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhicysn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgigtrj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ittoleuo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjcwtxu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ztuqoajj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hgoojwto.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oshmmoyi.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2docgdhrq.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2qkltuzft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiulezle.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zipnqnzm.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2iidlvkiv.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlwdqtt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2khzlbcpm.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cuguckdc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ogfooyay.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2witltkva.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbokcbpr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2nohbiitz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzbbzdh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ryenvure.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhqjlnst.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qvbwxqnm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdzmoec.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqivbga.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2pjovbncw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuiyyqc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2urljlmux.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxafdtgr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwtbqub.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sywarwhh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mfgzikeo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ztquzfyu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfmawuw.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgwkarr.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drqvtodo.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwrghii.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkzhngf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2qecgeuqk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cimrirxx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mgaplabc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obyvakmv.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsnddlj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyndojbr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbwctaug.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eipcatdb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmvxnpm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhukstk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdwidzg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ninvbsuj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ylajxcdu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ptzdhegn.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltredeub.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfuifny.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ozsibkov.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faayqvvz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfsoytkd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tjreuwgm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2wyjdjhip.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2eljgfeoh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muuuiwnz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdjnjjb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjzdkli.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2tochmoam.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaubgih.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kelbyirq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2migamwzn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2urkiteoc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2onpblxzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjrufqa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwhyiza.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzwoqxa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eeobozxn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2abnretcs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkasosg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbdbrrm.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2igjlojdq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qthilhzw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtehbpz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2jhvnfpvq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dwoxdfiw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxjenuh.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mvykoslc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejjckhfh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdmjdcw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sptdaoma.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrzxubj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2empckjgl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pccnzdad.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2manmdxzk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xfsegsqc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioisgvls.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mvcjpzcl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgaxcmb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lfemwzes.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2egquqtlp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ppzycdsb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2stzmajyk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uttvqxvr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zaijlles.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2rkisppis.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bglzatsh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dxqvxutd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kmykndsk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqmwtzk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zbkgzidk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2daxrgtus.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2trznjkrj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vzufsywf.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnhlagxl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2haeeearr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqxnmsy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrwzpjl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cztmxzhb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tnlmpqhq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plxueijd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fdredelb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqsunlxs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2edeszcud.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vezapvlc.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fotgzbhr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2awsdcqdq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gcxrcstr.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmupksj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tezcgjvw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uschqajt.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ysiyrtrj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdhattnh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2moizmhsz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dddiziey.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2easzvgme.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ntyuuryr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbqrenv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iuriogue.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnfzabj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2skmuzffz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wewxxvqs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhktknx.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cmmwnryw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2uverniyx.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjyijhf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkutaem.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qwffmxyv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2htkuxgdm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2jydujjnp.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnbwbgj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2byffbtmv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuzxlpz.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sazjnxzw.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bmfsnzhi.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnpmaqbe.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2gqiwgpqx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhwfuwe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxiogte.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2byrqfiyy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojppygzs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2citfwafl.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2izknsnta.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thorvnck.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtahlfc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvkpjxe.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bruzkfdc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fclacngq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eberfevv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dqezkbmi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snvhbwtz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nrnktlwt.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnixdmjd.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwathgi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkhltxr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtclvqwy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2jfdozwxt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrktjhp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rlogwpgz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdbrqoxg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yxotbyrq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sgffbbqz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zpntvrkl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuljpfw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tahrqbrn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2knycggoj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxgfggu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhdreuv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2roftveuu.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vunpdzey.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oleqmjof.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzlscuor.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjfpnak.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2sgowwzlr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2grnyrfgm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjycilg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxtosbg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvtygds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2orljtgem.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tolipzzv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qxxvmxbh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxzrmtyk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzbgirf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mxjjpokh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxysipff.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjhcdyi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2itpvhxzr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrsqmhy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nvsvqcbj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2noljsido.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wbidsnup.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pfannxor.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ejahrefg.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtinnow.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdfadfw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oyskised.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2emtbcpum.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2esevvtob.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2erexrhtl.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzdgwyp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dakdypea.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2shcaovev.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfixsfn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqbxvjw.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kydxsmsn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ahptvapj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqehhskg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vlkxptct.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2artjbeuc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjbocsb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2byavckas.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kukchgtr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2yhteuhps.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2txpoegjj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnavwerk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wknvgccx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfoomah.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbdapsf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aznyjjpx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xnxsdvih.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyddxbsy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnlrjct.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2wehamsnw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zdijkhhj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jryfgpvx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmuvuxc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvwwggi.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdzggzq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwavpulk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2iixktoxe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oasgonak.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kspvzgkb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiymmbx.html


<!-- 参考信息 -->