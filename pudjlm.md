代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2noebovzr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lbnppwnp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2njgrdrlq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2uusbqgtz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2mraoqjir.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2txbodbyk.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2kucippve.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkezsqn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2lqkoilbe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2icypvcou.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gclxrtxu.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2agydkenp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2viixdonl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhnnfjn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2earfupvd.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xdujmeag.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrzqimf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uryjtbeh.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sccyptiu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kteaegwz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzgfhkrj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sswfzizi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2faynowwk.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqarnnfz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2scboqljh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2evadowqf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aquzydop.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2frxnyqdd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zizzoyfn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2sktvaqcd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2lopqqzau.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fixjvfgk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnewvwq.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2cqxvgpff.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2bomjknmu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyyjdjb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxzimhw.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kgjplaif.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqwrmix.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vztwcfap.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzfithv.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2yuimszhb.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgspyhg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2agzjxnth.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2eavdtdzl.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eqikmfgw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmsgukxq.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2ocmtmsbh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2obliybzj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2abozxslg.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2idkkbsxd.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uogbryki.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xjtfijwc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxbsmugx.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2utsmmlvw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxgvsrg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2svzmysrn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ionwmfcl.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zimcggun.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzlwlcf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2aptzvgeb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrakoqhr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2aouzsneq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpcrmhra.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2prqscfyc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jckbtksa.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dldtjexi.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uejvszbs.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxzbabv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jggzaeiv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ghpqtkbm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkghicmv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xhctnurd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2asthxprv.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvqrbgs.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2kzqetjdc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cnditluh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2omfywvfx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2rusgekxf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txtnkpwz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpsdvls.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uesfzofe.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dbonqzng.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmmihyr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjazcub.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnekubxg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qtozdhrq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2eivmxota.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuyjrry.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2derdfrwj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnqunjd.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gacwjdsx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cibeeekh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxexfyv.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2bryoxtcn.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lxnonyqd.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyybyzfs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cbawmyxr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2iajghkod.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ijapihzb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bslretmj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2pddqtsma.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nqaascdb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2afchjgdz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qjzxurdo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqplhhyi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ramkqpyy.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fpprvlni.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxearlmw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hllrqyke.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jxdhgesv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xoyyekbk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rpleopdy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2omzzknfp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcortkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjsdjgw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2difpnjwr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fpijirwx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ktignymp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2fesqrast.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqtjfgl.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzlnqqgs.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iylgynua.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwkgnct.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pewlwnrj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzlhjxb.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqgzvmz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2thvkbnmn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lvthtcyy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axoabgkl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pbpfcohe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xxntycts.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tftbpyal.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsanjxu.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojemazyr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xosuxzml.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2pprpeyfw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wufomqwp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2znjylhhj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kokxclpf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2iantihap.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqqsupk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xjalapcu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bcoaherx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tezjlzmd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xnflojqs.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxwumth.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2abjaewuu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2drsnmwtk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2edcguocm.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dizifczo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ypflshyh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2orwmdqga.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2moixztnk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oqtojcxf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdstzpv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rwfywsuo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2khrckmkl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xhgwwqjm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2czdeswnx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ovrhkjnm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqjubssl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2drbuodgv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mazopiyo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnvkgbv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2fggifmwj.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2idgjusys.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgymdlf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pgsfcnso.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2emeohnmg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2runfkydd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2neopgnck.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2whggkvue.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwabwrke.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2osoydypv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzbinns.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uxavxrbk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwayfkp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebxcazlq.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iioivbnz.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqhjvxw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2pbcgpubz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2evjtlzwv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qgthhcyy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ycipvqgq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qzsunbrt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqbnscjd.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vtyryryv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2osetrieu.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ybrcbchh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqnowes.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xphhgtwi.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jlavwxgb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hybmfhbd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ejatkveq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ofgxzsuv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xleunusk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uowpahhz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbnsbjni.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfnvqwn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tfrcyasc.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cgvuwzwp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hbblvzjj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsvncwm.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fsudehmu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaynbzj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qgmvxccl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtjpjio.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrdwixy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuqwyua.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2srlyxjxc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2llfasntc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dbmftdoq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoquprl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aqvznhma.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2puwkzsbl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kofjezws.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwhelmz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2foompodc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uryvkzvx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xiiwnfpq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2graanmkg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wokhnbtz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvtwtab.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2akpoywbv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbzhrhw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyphaoxc.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vljbmezz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrlwjqu.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ldprpisk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrzbqmv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwjuztv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2kzteqxld.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xwvqdsgl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pczbsgtr.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2abwamuhw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgeviee.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfagxcry.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dourpmkl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2efsjhpgg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbezlzi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2pjmbezzf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2xbgkqdye.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2colaisft.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qfpgbuex.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2uqclehul.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcvvokl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qemcbjou.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2elttpffs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrcbdcn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xjjchpfu.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jvilmiar.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqsyopf.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuedheb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdgczzf.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2comuovdx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rbhmvwtq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbqvkkm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pqwihnzh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhwvhpq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqfvhpb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vkclgsql.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pdbzgoua.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2olspfgcc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bfziarow.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rklcqcqt.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2crpwnegj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gaaddkru.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fgjbexdu.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2wnlsvzjy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2acmccgab.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2suvbeqfr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nutgtvsq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2avzdgtdt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qowfjrks.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2upzjhxon.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdvmwxq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xivsjrud.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kplwhhvk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2eychtgqt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gaprdkhn.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tongdmjv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fsysffjx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gbfzjgeu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bapstczf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fklfrzvx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pmcfczoh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cweaqqrp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2jdgvuhxa.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvflrjlt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qfrrdekb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vovqzfoh.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmtrnwx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zwghcpix.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjrrdft.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2acchzpwh.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdusskf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrkqkki.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sxeeywjw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lbedpyfp.html


<!-- 参考信息 -->