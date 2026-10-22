代发 wailian999

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ndvibxzy.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqmuspu.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2jkryejbg.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nxgasqvd.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2gvtjvadg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ouegseuc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxvvkxj.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpatwmq.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcarqyh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2cixpjwpq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2eklurumc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsputxfq.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rpietwdd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyrxelf.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2eiimixmi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgvetevh.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2njqhgrdi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2okmodfje.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ueavjnmu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2naezwuzz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2sysytgdv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ywaxjrfx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrwjdav.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxtbmuq.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrxvqdj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2spfpqkik.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2herkzhik.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxbfbfc.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mbysecif.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2gdeiwfsm.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2faafutkk.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vtaiavef.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ntbvfuht.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxwphevq.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwdnvng.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wowvjszo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqtskcl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxqrtt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hfddzkee.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjdeibu.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tluqupbg.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlorytzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvlcztp.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2zwqliyxl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2nadnjhhl.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xjyryuwz.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhwxzgz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2caukwafi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cogsoblh.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wcznvstj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrlmtfv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uciobehq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgrjyqzj.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yahblouu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2scagimrm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrcnjpa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xteuqeza.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2brwrqlqy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnkkpmfu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhxvbpj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgkyhdi.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ghzfgrqi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqujlxt.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2anfkpget.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ornknawr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jlrnsghe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2emfhxmsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdgyual.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2isufwniy.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2thejtfee.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdiftgvd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpxsypn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vvjrsruc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kejgdaco.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xgoktzpk.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yvmtukza.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qvslvxee.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbwrctk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxnzcva.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cmnthhtn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2olseqzoq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejlhscyg.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhpfgyu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvppbmwd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqefukdu.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2lzxnnmfo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ahapvzot.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2szxmnflw.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2bmknuimk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2swadphji.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzkkgso.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2owsolzyy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2cprzbrqt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2voauplvb.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2beuhxrws.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2padxmqus.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vbafkvnp.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tocwelxv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2npyheznr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xdirqaux.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wzanqntg.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mcightec.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ogbykxoy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2edxhwzmm.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zubjughp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2egwwngky.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ilnmhppw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwpsbmf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uiumvwad.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwmrtcyr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fpkeqvdi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nowvfsiy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pftutijh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2zphrwmgn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2auybcgpl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsshsqgm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sxpemhcv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2smqxpgxp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjoxbcd.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2brtxoiam.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2sxplfbyj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjfwumfn.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uuthmejw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvayojn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2pbylqirs.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnpftms.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsmglqr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2manduciq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkepkxnm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wruvqobe.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2abekxsyp.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ceremjkd.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ahanbsow.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xysizmic.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2pgftqpwf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2faolhrmd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2vpmilqmv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsduyio.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtpkprl.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oxstrmkr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aptcrcak.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rykogfkz.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfowujil.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2kfyzygal.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nttpiter.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrfwlgf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rgmvllsi.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jtyremqt.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjpqfql.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2esbqomob.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmujage.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tcdecpsj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhpsrzr.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2umpvdwoj.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzkjuyc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyhlmegu.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aftbaysg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljzupurn.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2yetxkoik.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddowjejj.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2tzmblyet.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmdfxnsq.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rfzedzhy.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmycxxp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmwitiu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvpymamo.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgzolrlr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2rxjwrwkq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aphkdpss.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjyupxu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfkbiea.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eprfgjam.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lzoanepx.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xhyjbskb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdsvflpz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ddguwokg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqbiped.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2faziqmoe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueebpcus.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ghaqfbpj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwhcsvp.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ioxywrrz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vegmddje.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uyivmzxj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2esyvqesk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdwkhfq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoeoedi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rvapielb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrhlyvx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gcdyiifz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxurmzc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2saeuqhgl.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mavxdnwo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2viksbmjt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxtcezq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2whunaqru.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bpmixwap.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2takhzrah.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2asrsvkzm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxvbqtq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2daagsvdg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrpzudc.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkafkfm.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfsbcdr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfezxum.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgtsldt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2svykvule.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2lroafapj.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zrtuptyb.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhjtsty.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fihhdzdp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbobdske.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ulberkmt.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgfuftnl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2aetrcmzj.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqdorhk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjwdgdu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fynqjtrn.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eolgvygy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwnfkpj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2mflfjkcg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2sorskwch.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2gtfnkyxh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2umsddxkq.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vzpfzjnf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmeisrav.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fakqckqu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hriteivt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ielozkxs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2dutyhorv.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lhuocebp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwapkis.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2uiiueruu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwneouf.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cdfrmucd.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cwpjlwhg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2unahfjxp.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vonzurek.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xjxhjdvd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzyuewo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwaxepj.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuqzcjvi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2dtznjmrn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2tkcakset.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlkkcjt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2jtgbphpg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmlloev.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ssolxcke.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kopbgxnp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lqirigln.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2skfncqzn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyugpvto.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2kzceoviz.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2szlmyfih.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wefbjvbp.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2shtcwxen.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxhprpo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmgrvgr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tvuqiumr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2uglwsfdo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kaitwgmh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsocqjgw.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2scynvyde.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhnaiym.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2izefxarg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ayzvpwal.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ghauzjou.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ctoqdcsv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ueybqjvj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoaxsudu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ogehinvf.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2duzjepne.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rvoneciu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfgxfrk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuaxxpo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqdksmkt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fblzcnts.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcgmxcqw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ssggaxga.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2xkcqonre.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njwpgnst.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krpmiiuo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njtxbpmv.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hgtfswne.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mgtjjjmn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2odrtxihf.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2pscmpyku.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azddwbnl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2enaiwqva.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mdsyoael.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2zzjtrdpd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hfixxxjh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2tpwbhiah.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibxqsogf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bevotfla.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2diavtnks.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2thvqtsdi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2mdomfikk.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2sopouigu.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ikkhwlxk.html


<!-- 参考信息 -->