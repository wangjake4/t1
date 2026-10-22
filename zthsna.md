代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnezmwn.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oryidtlt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ysltcraz.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2knrjwrrp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2wneorexn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxwjfkw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwejxclt.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gybmkfgh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmlxnlh.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyvehgq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2bsszromj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2keqezjtd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrymakf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdvvxyy.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2alqppywr.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2khxsxqol.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfmoxuni.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2vpztqjux.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfuulth.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsmbqknx.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2uztcavcv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rytitdkh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbgfbtf.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2netyyvnz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrrqdky.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2cigojwpf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtxtlwi.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtclagd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjftnxk.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2vfiseaud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2ignyxrpe.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wirfijue.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2owregqfh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhhndhj.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfsowwp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2mimopjdq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2atcprsfi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nphhosor.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhcnwxff.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoncfwb.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsaaofz.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvpykai.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvrlcsli.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rslhgsvj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2bgbpzrmn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjwyhey.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2nmzpslzy.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qdkwtifi.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnnqoyj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpbjstdt.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2psglfvwd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsbkopu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ltnkthzh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzqdgopc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfrtzga.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cyilvqny.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2eqkzsmxi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwvmhh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2udavrhqy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwpfoip.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnfchoy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2violutrt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmtdbzb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxpvlvn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmbfste.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvlvcma.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htgcyuvp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ykwwkjac.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2peffjlcq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2taodcnud.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjbogvu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wrzinxjw.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xsxzxnyr.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfavpafs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mnikhjhq.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbdjpbv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxquape.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jyruzutk.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pdrtyfvb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfefrfnv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxtvnew.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btedkzxp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rrtkczyc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2lktrsazg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gllsofng.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aznbyjya.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2srtbgjxp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2epqkqqiv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvmxggw.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2idpoqpwk.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmplsbj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bajwqcxj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzwvatj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jsouxzwj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqazcil.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fuyopgov.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbsfgiqy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfpxmjy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mokgbfxr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkbqede.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkbvzxpi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2jeduhnbm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tonvsnmg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rvyfbdyn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2crveomgi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xllkmypd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jglszdkq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtqsyyr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgqwfic.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qixyvmsk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2bhplmmko.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oratmtgn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vllzptxj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gevwlslo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ekipkqrq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyevdnu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2yxrywafi.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ysyfumwv.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2rifcgiav.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qnujklhx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2huzwneri.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2shhbuzgl.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kwbbrnwr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpkismw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gqykzkqo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruqnqwcg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwdqyxu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdjuvocg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnpdhza.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2edvjkbbs.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rudlmfgj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxfhclet.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhrsgcb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2emluonhs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2tajjtwru.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbwosbri.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qxprkycx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnwrcld.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvzvoxz.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2guiinxgs.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmgceny.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2addkjfxr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ruamwggh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2unopbykn.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnnnuar.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bccgqltu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bdciauqo.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2nybeckpg.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ishxbwom.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbopusn.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2oxkcgvbr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgrxrdjs.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnhtqwjq.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdowtadf.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cwgjkzfb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2opwpeygp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2saagyhxb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2lumrzyhq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rixurlkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2aixqxwge.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ldidsfhn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2glcjbpag.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgzhkkv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2umcyklnj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lountjei.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yanfrrkd.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfwstvr.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaecsjf.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrtlcoy.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrntzhb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2lnkhkjqq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruanhsvm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lybtkhrg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpmiubw.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlqvbze.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bczhxnob.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmlcqxjd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cwebpljn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vegeoozd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrvksyl.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyafpai.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2koxgcgwe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2brbahnef.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrfmsdw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2uoswgzln.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bodbfnxm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxfnfrz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnyvhts.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfvzzyp.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhjluphk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2grytgjmv.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2twlgclgf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwabzoe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2trobexty.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqonlbo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2swkzaavn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qizrywac.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfscpre.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oripgned.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbxliejo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdcfpns.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dazkemdk.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fppexqkc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxdwnni.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zpalsppd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alpjpcpy.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2syddrosb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2cikdvbbg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgsxqdt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzrptcc.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzmqycq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcvjsear.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaxlyjs.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gqsnxmat.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuqzzmb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fhggivas.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jlarlszb.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ttydibko.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbddpxis.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nsahrjoq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2crxmtogq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qgnujzzt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jakpujmr.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjqpuyb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpykorvi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zuytrybu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdfqwuj.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2hgpcfhxm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hrxhkosp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mensxhti.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2foaymvoi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ibywtmrb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbnwmlo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwmjyka.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkojsvg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrjoqii.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2iogaohll.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmucvta.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwpawuf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uphkcynt.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiykfsk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzsxvfs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdawjfe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ilrzybze.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbkhbbg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2qsatwyfm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsfwkqk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzivbmj.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2urosmpls.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuoiyva.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iexrtstv.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2uwepgukn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlpwiaj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqvsumb.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kmuimgxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2lmtrribg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vzqkrsfx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ofeokfmh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tjrpnmay.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmvkemfr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2rztzzasc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcpaitry.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvgecbk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqtkncq.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2zqalrciy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2uabogcry.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxmpipg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxxsdrc.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2llerpixd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvkovhvw.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2weizuwuu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2luxguzlf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2gtqjyrwc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gijrcvbr.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2osnkktzc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ygonejlz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2glbqoflq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qdcbzxnq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2avkuvbeg.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cmvfdoex.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nsbcmhly.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kgcwqmof.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uycskhfx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnfctxr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lbgwlryf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkgwyptb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxiijjj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bndkggpd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpxskxr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qksqtgeg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cybtolkn.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2koaxaprg.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ppouxttw.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2strrolic.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2knlfaqxt.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2phjxhbwi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmkpsjs.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxdmifv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtmksfj.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwuknsp.html


<!-- 参考信息 -->