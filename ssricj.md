代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2zvmjxvvz.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2dopnwlgg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2wpnbwfsn.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrbziqv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcnpwxd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oxicudnp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmqrwgkt.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdhsmsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbcicwt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwembvmt.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxpvjpe.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mvybgkhw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzomhabt.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tcutjotd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2eddnrflh.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tedkdxdk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2kewgeiwt.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zasdrolr.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ebfirhha.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2azahrzpz.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnfzozej.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmrwakn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2rlnhkqmu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wnzlnuhr.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpmqmda.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxvldha.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2clrgavuw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpcqeur.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2extxfmol.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jrikmifa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ancwshwa.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjfcvtx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbwofum.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktepxmca.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgactdsr.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xnljvyds.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2mesoxdpx.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2dytiktmo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrcyjqh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yrphccmy.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cikdedxe.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iazeflgk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2brknzowb.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxjzgrm.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqwygnm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tffdgvjn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2moqnprpx.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2onovpmcw.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqiqhlg.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgfocxq.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdzihrz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxvlrpu.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nrpbxqsx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irbqhsya.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxwdegf.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2yakmmmiq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2njqnjjij.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpbxues.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2fyilgkyy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkxayiov.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pjznjjsv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ublhfuzm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqrulua.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hznkjulq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bifqcupn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wijsbllt.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxyltca.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rswhbjfl.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vnhimkur.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2rugdqtux.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ldptdeav.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2fesakeee.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zionfkpm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rkiwnmux.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oatpirmr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jjssvyqx.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvepgmh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ezbzoffk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfqhovk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbfivvib.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uflmeujw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ydnrdllb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2biujlvtm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjfqztl.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uydkfpxl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyokkir.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqcdyxul.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqvilgn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zkjeiygw.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lzecfnif.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2btknhhkq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzmmlsl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpnzmhkf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2whkkmyvd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxtcxjk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbpoohe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jlpnwjpa.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjiychc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgzyfkbe.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vesyrslc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rzofumcf.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2opfentwg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2arffvnxm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rxvmxwne.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxahaek.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zqcronbg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljywhmgq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2nepfhyvz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmeskeg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2azcspcfc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2hfvzvzyp.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kqetxbtf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kzsdalpv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vfwjiyjq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqtusss.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oboehuqn.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2alouidgz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrlbmqx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2supulllz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2opzfvkmx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2kplzfzsy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fheeuayx.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xpickoqx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqhyddh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aiinnwks.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xjqsdsoz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ewrciwec.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pydzooud.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fnymhelg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2inmumubz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cxyhwsbq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rolqsgho.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hajeuema.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtgfkva.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvxcvxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eckmfnwy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nmslsqgb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxbjxsw.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vpflasar.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2euyiwcjw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2lptbzmpc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eogtkbtd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nzdkrxff.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tazdttje.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gyghcgti.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cflvxwpo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtlnwyd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2obvwqmgk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmammac.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jywedtom.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhmwplez.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfdixhq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rkouzhtk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhelppqb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jktyclbd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jssmyujj.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xmobydso.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqqcaim.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ebipknrq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmcmhvuh.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zayadolk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhesdvi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcdfddq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edacrlif.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcbgsxp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2anqdhgvv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2culaznpm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2etkpjrir.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vicvlvpw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqscoymc.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdujkny.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbfrllny.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjhciog.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwifycr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xteyyezg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvyctrse.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kkafeylx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pjhrmqqy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yfypoqkt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2trwstouq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2pksbisks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cctbjufa.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2aipsothw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlonuln.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2udeoeiyg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jhhlnknx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkttkds.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fhktwwmk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2owxxbjrx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gajochqc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lxieqfdq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqppyoq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwgbycic.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgekwst.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2feiieqji.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2cdskzuxr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iukiqjpa.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eosyfise.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kcykdtfq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnkhlrtv.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2knrgizhj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfjwgpi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vyylitdh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nseeagda.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dxsijvfd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdbjltme.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rcynaqxt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwuozrii.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrkhaei.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poqqksza.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyonyknk.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mranbxor.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzunjkrh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyqotab.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkamfri.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2drvejizi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2flmoeokx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jwrkoobl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdnfplo.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2sjnsycgj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2funrgdkv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ehmyohvg.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwtnhkk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wwktjqep.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bswymbyy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ducatzut.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvyauaa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2bdairxku.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdiipydr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdlrggv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkqesnq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2msdgiwff.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zkdjqouh.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvqprhb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bekjcixi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2tutkklwp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fextdatp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pzujjnju.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpsdksc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjeocux.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2szsdjefh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaugtmt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2aplxkvhf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlbuajp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wyyiootz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivtmmfgi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmotlyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2gcbfksrr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bqodnqtt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nprticse.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcdlmcz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hitlczos.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dkflqran.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2obcibcvp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2uhteawsr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bcpibzqw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlguqms.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwkbcja.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rtlawxwy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ygufjcfi.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xcmbvqpg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmvkybd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2obltuelz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnmuhfu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hygwlzhn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxteleim.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2txdqefwq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2tbrezbui.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuxxsad.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iqixkjfd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2awobesen.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbkwkwf.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfenali.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cpyneddp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrurwhd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2njjwqjwv.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zpgraliw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2pihuidul.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2oehtqjqu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hltgsiic.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wwqzkjys.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxvpydv.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2dsalqcqb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2utqzzuzz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tthadbuu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjfyfsb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jflbyiff.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuncjaz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ueuvproc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pktiiagk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjjrqyn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wygjvmzq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2pzvuxhqa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lgcbwslz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wkbydysu.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qweezmeq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ecnpzaxj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwnolpm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oelvknvh.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhtqrjb.html


<!-- 参考信息 -->