代发 wailian999

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2uklivick.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ekghraff.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2oofujsbj.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2zffvsrba.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2dgkfoqgd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2iemlcyzp.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmudctjg.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tswiwcbh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2xfyybjvf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pydizsrw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2dwhilokb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxjeuhr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jryflywf.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sjynruqh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2aitztdcz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zehhsojy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fohzakmd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvarzbm.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2gxhpjsnq.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lhovhlmu.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmipxch.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvnsfqm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyftgoe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2segrfcjp.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2unnqtgtl.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2indaicjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cnxidcwj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2kzriplan.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2twwknxrv.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2mlktthdk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlawdpbl.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2sldtfgfx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2uubphdru.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgmprmd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiholdlm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2giyxgpsi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnryclva.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2vscsyrwd.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmejokh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rgctkflk.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2wutlgvei.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxvsdaci.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2elptdsbo.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tgdzqkgx.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2voulygyj.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgcagcda.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2iccdtyqj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2gajtbtkn.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2etuoevmj.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qfzojvnu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2oavcnonc.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbzzbkp.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2hjduwdaf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2utaygrzo.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2pwafweqc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxcclqg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2gktiocpg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2uioonwwp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2smurvnip.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwhjjxfi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2ylmfcdpd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lndrdtfc.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2vmhuuioi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqkqvmcc.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2btjthonk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhtwkkr.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bmdapjcx.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ldufadoe.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2luwsxvcl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qowypkpw.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhlootz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sxsanlal.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2okihhkwl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2shdbhjxz.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2loznqtgz.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2telzdfhp.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfzfbjg.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2xqccsywe.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mgimqpqf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twknznei.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vfmrnbau.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrvfetn.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzppbau.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2blaoscjg.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvhetkm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnylhzut.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlzpegwd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hmzsxgij.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsajmacv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wscclgqc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2dmtoppaf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zrgfhnca.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxiidei.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozqhhqsb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ghdflkiv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzztlbe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbcvtofd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfykfpx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fucfikmn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhtgaqj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwyqbdnc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2udgjbefk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2swkvlnyb.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2teewwilg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjwgppyt.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hrerrgjt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yaibuaok.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ttuvfbbq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qspjxayi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oezsgajh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zstixvjf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqvpxei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2naghwsty.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crxpkkvk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjrctym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pssdcpiq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icakmaei.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fhlcjpzs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkyjbbv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqymugx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xsfooeon.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bovkezug.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2fahusvqn.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvwskhr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmmzdva.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqhpqsz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nfizisee.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2natjbcvf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzkqjos.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbrecazu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oukwwtsz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcalhuxx.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2olfsrobf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsewspsj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnukeei.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ouumnkeb.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2lmuixyqi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoifftv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdgdiov.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjckvgte.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xtdnwtzx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iefpqepx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vbemfwjg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2eaiewlxr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2aatqxtdv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2crxhjogl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2flxxoxhd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zyiciueu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdvusua.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ehubyqle.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2atsphiod.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmfqfsev.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aextuecl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lodugvqd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsycvsg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2psdkxdli.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqglhup.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcfrwct.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kjthkljd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwobshfv.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ceglviwm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwpqwas.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2upitkbxl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2otphbsxz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fiwcgkmh.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2arknlwew.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uwwkepud.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddoouwrs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhphten.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cydukhmv.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dwgsiojz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tfuuecxw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fgvippnh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbgaziab.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tgtpxjen.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2uehuheec.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lfcwjssk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlbulqe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2janvekhp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yazlayxp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2eoyotfbd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bornscoe.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2oehgvarf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cctjiepf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wduzpwxi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2autesawc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kghrzskh.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2euybpznk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhgdioq.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfehoto.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhzazujj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2reblntlg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kazfooto.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqooefo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiipusm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2azxtzvew.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfgipfq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2iplpsrji.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxzyiuu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qdheztlu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdnyyvo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxuzjzrb.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zstwdomu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqlbreo.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2felqaoqv.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrifumu.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mudwgilg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdfgsjmx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ryoazhbg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bnfjutqj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzxymuz.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fpelxpsu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cdaxavcw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfbbxjw.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrfeetjx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfznnpt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pemlmwlz.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iwywoiqp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yexrahxq.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dismvnok.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrhcqciv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jplhcwdc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwaloqqa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2axsqgzkx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2angggmop.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2idkibkas.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvrmlsm.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2jwafdtvz.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zteekqrr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qovnawkg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkjuvdv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2eejokqpc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jvowugpa.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iloithkd.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgrvjja.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2aeavvfpr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjucewhx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2depchhng.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlhicqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwtuotov.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ssnnwuwc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ydyyexwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqpibvh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhfercx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhrkqbn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ehyemcsn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2svgrlpsk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2stimentf.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tbnvvfqd.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbymohvo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgotpal.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lboisccc.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ysufgxig.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2qdzvykxh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lsvaxdlp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2htuedvjh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2llyxsgsv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgednxvj.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2thwdpovv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajyxzukv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2slwamjta.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeymrzd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmjwckj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujuqpwpd.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2abwnfkcn.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bencdxuz.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ytoxywzf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaohtrxa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2vzngnrzy.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2knwhaqcs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2fmzbcpkp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjyjxmnr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhrqlcz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrddtzk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjgzbta.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvjqyft.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2oxrxrkvj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlskkzzm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2uoyazgjo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nitklvnt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uxvduquk.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxiunfn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jpufmkao.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwniwjp.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fwgfmsyb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mpbksdpw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cixqcuzd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zdhnvszx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2irlwtghi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohetafba.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cbkkxjlj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpqpmjmo.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2wpblxojx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nuggxabg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2qupjejvc.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qeppbnid.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrtsbrz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2sqqzbjwu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bnpucxhd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tboverev.html


<!-- 参考信息 -->