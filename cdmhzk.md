代发 wailian999

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltblcisz.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2lbaefekr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hazofgbr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2nopwupvf.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oitgxlto.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zcevnibn.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwzoizf.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2saartect.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2txyyigfu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxvomgu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2dmpjlaly.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2eghqbgvu.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2gylzqatc.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoriexi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmgrjmu.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2syuqnvgv.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2nwggfzsn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsostyqa.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhkemda.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2fupmzvkx.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2vidwqzjz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2nyspgrnu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsajqop.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmddibyt.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzxbxqc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rptcusea.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2hdangwtr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2csurmcot.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbskndn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsrlamdn.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxhmkuk.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2cwcpvlbd.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cdpuysyt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ytkfxlse.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2etpjmfww.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbcwarqc.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuurwsi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fonfvsug.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tlubqtpw.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2lqeiaojn.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vuywgzqu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmhvkuka.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ycmpibbw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqvbpokz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxzxszu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2brjddsql.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2pzazjpzj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdosdnkh.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fncmpuru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykjlgpar.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hkqigngz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2skkilqkb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kppanofn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2prscyoic.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrwzzsf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2woairgpk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ldygvvoh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2hdbiacxi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwddoqz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjjurna.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2feujvqlx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2crqcdisy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvlpfavo.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2viaykeco.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cflkzjwj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2srytlagw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxcffgf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hluyanev.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2omtiwprq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rvkocyrx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkeqwyws.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrrwzsx.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tadotmwv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nhquqvbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyfatgc.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nswxjvdy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tfwhohcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ogdyayvm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gtyrejuy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjmgreg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbnttvx.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jumkhvis.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkmtgxj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvludjh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uqaatnde.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mstcaxyz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2stdtiraj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ksywxteh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jipeieyj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqzbsul.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2grkgrmcu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2krggrefy.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zanmqhlp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwtokgb.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqvytia.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvqflpon.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgeapes.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yexpkzvq.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzsypea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlcfvex.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ewiicuhk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzemqiif.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2otnmtcan.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2svexysoi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdncnke.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzqvepoj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qttaxumb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2swhlezhp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bkwzputv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhxesyo.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgaxevf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqxbcfc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cuupxewb.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdscmkl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuvcvhy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2wyxqxayr.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yatcqszo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyvttdk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hwduwxvr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2krvkjcos.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alnvfhrf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgickehg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hfepevth.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlluqta.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlffjyp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2curpunuf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2erkzhzpl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpgnlxd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nyomiics.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2awyarlno.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ipewatey.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdwqeql.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjxczzg.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2azyozfiw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yxublmmc.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnjybwk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2novkpqks.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ahkvxgbv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yrlemzyb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmsfdmdm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxardsd.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yhniwncl.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lajtzcnz.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2teuejgmd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcezszu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vuaqucni.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2vmbyetpz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxdcrwy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2kggndntr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqqbdrt.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fznaeaun.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2dthzjfim.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdocpad.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fjhrljow.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhmddap.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbkfymb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nslrewaq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uhweoaww.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkbusef.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jndcggcp.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ydquukap.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2bckiulcl.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jujzzgoh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qteuswzw.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dwuvwgsa.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tjnkvnzj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vbpejghu.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzosmdin.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2maasigim.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzhhnsxi.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rkremxye.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xczjhvxn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pnyotkcf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdqivjpz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etlixusc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zfcmaxoe.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtgbxui.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkiehkwz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dzoqlwkc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgvlosn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgamkrmn.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2urseidal.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubovwdli.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqpchob.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmhsdwo.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwqhgwp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2onpdqnln.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bxpemzyi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtbagail.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cqepufgb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsfsokq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoululw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjckwnx.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2evfxedzm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2woyqwhgq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzlxrqa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2naguedlb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbuioxet.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rizvoron.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkgjlxd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtwawqr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2owklscce.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbhridn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2irghysee.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2bppchatk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ekzpsrzd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfcejpw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2akwqvgzw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyejguo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvcblel.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tfaiehtd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdmbegs.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvgwwxj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tuiozyjo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2twvawjsr.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ddeamvay.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhiytls.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtmdaog.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhiiwlh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qnifapvp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qlrgkxxy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xofaqcvy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vveygxzz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2egqnaefy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ltdgluyv.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhzraauf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nobdinxf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2watcypjv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvseomz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ujsntjoj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gsxbhpva.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2qryhmbpv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2niyifxjl.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzgnvau.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2zcrtyiuv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vatdntjd.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqocukx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqjwtae.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2caoeaiyi.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tgorztum.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzwyibx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iavbvzbk.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2aafsmkrt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaddsklf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2laymxcxa.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2mdznvovs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vkxkumnr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmtulycd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2olunkqwj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2npzssgjv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdmnqli.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nidocawa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvynerf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wevrjhon.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nascqzoc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzigtpqz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2etkpohyk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2qjboglkr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mokjdbwq.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2czxuygks.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjikvzh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2rohcuohx.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2hxbqnyvl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghuchtdg.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2szbokauw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lepavmyc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbnibup.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2iqteyrke.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxxoukd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2lpujrwyw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgheqkij.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zalmyrjr.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdisgzyg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jggvagrq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2paksdisk.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqtlphql.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ughlaeon.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mofsgdmh.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2revodltq.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kqflphmd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyhlgsa.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxycvjbs.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbfkzjv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wegfhssy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2keuaivky.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mugxmbbw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ofahsmjj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzcgipd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vpljzrjb.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxptirym.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pzgydzav.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfmduvh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrtylds.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwnbknng.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2znxvsjbl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hexoxmdf.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2erwjuswp.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiqmzfg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2imhhfvkm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhjihtfk.html


<!-- 参考信息 -->