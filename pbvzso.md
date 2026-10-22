代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqbbtlrk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2vticbnof.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2zvwpcvfp.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2aioavqmy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2aprebfrc.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2lgmdhkse.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2dsnhlage.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2zacrvuad.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntvdreeh.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2odlvsyfo.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypojaccb.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2dzdzfybx.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsapldj.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hmpmlrpf.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ybkvzfax.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xibwkhac.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdpievu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojpyleqh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fkpqnswn.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2avuyabfv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ifpuvjhi.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2uoohwvol.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2quogmqdb.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qpyeqylk.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2lyyqrqjs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkedmuc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwmgrif.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbglqfec.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2kzppaywr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2peoexarz.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2relhhgje.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmuwponq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhktwjd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qliveusm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2epbwsyny.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxvrqoq.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2dlryfpay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ynkaauhc.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnzpxbd.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2sfzbtmll.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2klyfqjvt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cckiwgka.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gckfqpna.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmneoslq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eygwlwgz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nppbtvrs.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pbdzqsjr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2axiqqhlk.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yzkkebal.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgzqoun.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ooghldpe.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vxckrayn.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgpsazf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2uwlwcory.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wxodhlrx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmasghb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrfhpne.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kikghgwf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rspyvjog.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbdsoejk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmnbdcn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqexlco.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2eseckqes.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2gflmsqiz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mshcobrc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjpqisq.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qptnhwlr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2idthkvfy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2desggipj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2gqldugky.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkswvzyu.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjsrlef.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvesaipe.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ztluusdl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dpfuqrkw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nekqdvxc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmavhpii.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dkwonrid.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kcuzlpyk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqltroa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfrfcnf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2cnpfvoqb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2afaribhk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cafwfjer.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ejupfivn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cgmsoxdl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2nsypamhp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2notxqyvo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zslrhmot.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gzrxytyr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqyprak.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dszmtjcy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xiamwzdq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcoogzji.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ljimlwts.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2bupxlhfm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwbmrju.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rrioocmo.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ydhssvdd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2binnlbbb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yoggvfbp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjszbok.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rvzvnxwr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tqkwzzdy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mffbiqjr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmqjowi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vgccvzxf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeigcmxs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyfuora.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gbtdyytg.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbwblbf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzpswei.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hscmxpgk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbpozwmn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fpgbyxxe.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbybjivf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ebckqvxw.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxotpto.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdyxzud.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cpwpabbr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bqrmfpeb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lhtakvde.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xoocrpyz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uhrhljns.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2jwujfonq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjobxdj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2owfmaogc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qixexlpk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2owqoyknn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qaaayffc.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dcbjgwbx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wytrsnjz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alwpddxc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2euvczdep.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tebwphsa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcykmnks.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtavjcp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2skdvvcah.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2khnvbwjp.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlvjkziz.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2exrmotza.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hszdrgue.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuhvjob.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhxyxxhd.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cwofqyge.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dpsrrksm.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xciqdcju.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdydswvr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnywoyq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgldjuod.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfqlfdo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2odvvxntu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzbqzjw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xqfxccye.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgsndqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lgroaltu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihvcymww.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mzrddwrv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2msavdtln.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oeiueool.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2rhnsnmuv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bkxbkkuo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yflfawoy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ehorkpvo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdifpes.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdybfio.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2thocbihi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2abdljmlt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxsoxuu.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfnwoeoe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pgprrpyg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2nbgqwtph.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfisalan.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnitxuns.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qnnvajai.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnluphy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvvaeko.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugsdulrp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtntjsuy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgmojttf.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dcnurlcb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gmjrvjov.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ebauwtxl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2dvnlpajc.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qugdbrvz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjaqjcb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzumrhl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqchtcoz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wnuwwkqf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gjhdcnjy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jknunabb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cpinfsey.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vrzbnbsd.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwbxvnfm.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2maqqpgda.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2gavpxjvb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwnfpxb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wugkcxda.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wupromwt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nzgszkbp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmfrouzy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xzjelwgt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2oquhmrnx.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qmleslfu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pyydihdp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2emtkquoq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2elmlbsgd.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mqukvdml.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2njovhirz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuziyrg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ewejtgji.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2botoxlvz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gmisptvt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2yrwhtaym.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jwawxcnq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwelpsk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wmedkstp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kzfcuras.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2upustrlr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbmvzmv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrryxqm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bcmdjfeg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ceeibrfg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2caztnedk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2xqiagquk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxpnbrp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2piwqeyay.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2rzejyyyk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2btihbrmm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjzikpd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ginvgsst.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ugrhhmlr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2hgbkrfbx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjtvgog.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vnypuwzm.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgavwgu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2crnkppby.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fketcocc.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rabckfjl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2bxiearrh.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2npcczkfp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2lqirxbkv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwfqyin.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2dllnjnzj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zyvrpljq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlihdqj.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xoavpydx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmmzuyo.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mwppomua.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yiavoqyj.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkaeity.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwuwfrcn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rygdnble.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mptvrphk.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2pravxorm.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mtbnbcxm.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tluphkwh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mfhhekau.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bouyzuas.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxwvhfft.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2njzrhpdx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlksywfg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuqmhxw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvcbpaud.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2odeznoym.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lazvnqda.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmircur.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqrmjta.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vrkatsrd.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kcsvdjax.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2thhipkqn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2janhgxat.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2unbpnpbs.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqxkbuf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ykqtgrvf.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjvbhsq.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2syoifwjy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yustjrvp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2heumovyj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yrmtkfte.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzloefnp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsljxer.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2njeqqkvj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2soydswgg.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvhsqxd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fyerghvx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2duwjotnt.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nijevohz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2cazvzsis.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjstfqwc.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cgaciviu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfgiqdw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ychifslw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgmyflp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2cofblezb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxhiakq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qvevhpix.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxifriz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tprerxyr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mndscrpx.html


<!-- 参考信息 -->