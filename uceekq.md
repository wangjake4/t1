代发 wailian999

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xblpmhpw.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2prxzeeyt.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2gudiinud.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kodoucdw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2pygdyqcp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwloeoav.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ordgjefd.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eztyzifs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvlngkv.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2drcyfqmt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2hhykszak.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2laepmzut.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2cyfohyga.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rurosgdi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2irebbwfs.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2owcvogcb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvtyqeg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xwfyrwpw.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwtbiek.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdfjtzz.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhiudqwo.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sepvqtem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ldgvpdoi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlrddpx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuyhstbp.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zakhfcmm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsaxsezo.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2okfnhdnt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmqhuuy.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2fxlyrsud.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbchghns.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nhaxndau.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmmdksh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhamhgv.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2vujaiyed.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2jsgdtfzv.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhdybiww.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xeyasiyt.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prmiogxv.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxmwiox.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2lymkottd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxjypsw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2oanaocxb.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2yomogwia.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcijmmn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtmwjss.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rknbfdbz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isrfxaas.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2tbxldlna.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2baypaihl.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lrnucvoh.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmujvce.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2tlitaxai.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hurkbcvv.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2aefzuqir.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmoxwah.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2odhaoeid.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlwkrxk.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2krewwszm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iecbxdvz.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2xzodqqtx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebcgwmqg.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kwxsiksk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcdvykj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2aiudfezr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkgcayp.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2niebqvjc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdrafxv.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qabqjzkv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzdcioii.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlkwpqvx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2zkskcobu.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkprhgc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2itzwylfe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2echpdtlp.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqziwodr.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdlntpm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vzduxhel.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvgozja.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqsdqyt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cjglalco.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2teesqfom.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hwsowidh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxijusp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nggzvhoy.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mizuusuh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2blwflrdy.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wliirsyb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2swovkyzk.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2btvvpwcj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ggrrwdbt.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtetqev.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkhadxrr.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfctwev.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tipevpqy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vjddsqgp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqjtknf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lodmdlfh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxmqiuea.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2cssxnumn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2onbvblij.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziwhqmkn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzadstdu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xoumdxog.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhedqer.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xpilkebl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdfaggs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vtxaspvk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ttykvkgf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpbytob.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2leswqfna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvrndlwa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2osfrmjki.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoujcmw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfygrsgj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2otriuoka.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uhvloyww.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2usujmtub.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ginckvwe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2oywrmrpc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2zanmduhn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrkbpdm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hzinztni.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ocoxqtuk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2govwojaf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsasraz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2njjurbte.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2humfxlbr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dfhqdhml.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dduiaesv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pignlfcn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nleihtlk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2msxuqyco.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxtehows.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvqhlof.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xejlpijr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2psdixnqs.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjbxezzo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcjofvk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2auodutrb.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2eyalhieq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2iouocttq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2suvtgidh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lzcgfafh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2shxsoiyx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2strmkdir.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ejuyewtu.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnjdbhkm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2stpcwshl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmuruvsi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pwjgstcg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2awayjcbl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lyexfpge.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwowljo.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dajnflgt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvqxkai.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qunjbbgf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mekwexqe.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgyvxhe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2eineqoah.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2oyzeqqte.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bknuwtph.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2qdlvmgjk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkjzfycw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hcnlnuyw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiasmsq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2oatkvqhv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooafoxxt.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2exiiavyu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zujxptqh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wezmgfsd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsbceoy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yymududa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qekjlqfc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdhhqxb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2jusaysyh.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukkigkxz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rwtjoyzz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2armzdmvm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mzgkbzoe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2psjfqdfo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2oxivrvrp.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgwnfhj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2yixaxtgq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2dltzymwl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iodtzlwh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fmpaedlv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2atnmglud.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlgophyv.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxmcdfq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfddykx.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2oxyzscnr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vlilqgun.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ikagdbrv.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxjslky.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xsntcibm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqpdlib.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpxezyne.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xofcjlny.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxevtxow.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mjtweedc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjvprzh.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuymezo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rohrzmpr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sjneoudq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptozqhvk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucslglig.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2hekhcvxc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuykwner.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbfjkvd.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ledxwqgc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnhwxvaf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2opyjebcd.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ohqlclhj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzckclti.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khqcrwki.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtywmhg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uusvheha.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vzcrvunv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kowqgmpr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2liwggbiu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fqqcvyrx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tftejhqx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2awjtxxbm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wkrslfsi.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2pjugopgz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcyfmaal.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pnbztlud.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2abqweauz.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mgiwczkl.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekofxmxe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pvrivfrd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2plrhalen.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2enceszyi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vbonsusp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gxxzwejg.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ceulnvgj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sahcgdah.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2wdtmyowu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eclzicbs.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzgqrda.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2taadkggd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsuvlin.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2yugpnqud.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2znskhrso.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2enabkouz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvqlzci.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jhmkfnnz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkwyhzi.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2cwlhkdtg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2blcmyind.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2stmguxwi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkgeteh.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccodcakk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqfmrvz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2esygckju.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fsxyiuik.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgsjsbv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nenrlvef.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfrnfcy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2eenjwzcp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2geflnhvy.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2abqcwpzv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvursuyz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdzctch.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2prlgnzfp.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2pehssbmq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsugein.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2yqxfjpcw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwumiyyp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hvwtvihq.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwzylih.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2edfsvrfn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glngamei.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgrmsgb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2pahuzdnm.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ullvlpuv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mmyednrn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2yabjewhr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzovvlz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mwccfsjp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtypgyj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2siqdpnpk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2culvcdvg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2fmwqziaw.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgigtwja.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ttlillet.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qeputxpq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oyfvyxyq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2htmlnszs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsuqsyv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vdvddxix.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fjczktkh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhkcmce.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sgsasvla.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqdnxjh.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2oncnegvk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ibckegyk.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfycfjs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2maanwogw.html


<!-- 参考信息 -->