代发 wailian999

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtwwbbg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2duyxeykl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjturtcc.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2ptkfxtuj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmcqghf.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2sgvoebmx.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2aodgsvoc.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmqpsoj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2svttnahi.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgobvftc.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjzclkaz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2focxkpjl.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2hewmnztn.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fddbplhz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwjxela.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2igyctgav.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2rruhmpny.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2krsprokv.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxbwcyh.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hycyywly.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2eosdleus.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlsackr.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ucbbreud.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsovnvo.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjmnkkh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iheogbqh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2mncyrllg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2koblrnyf.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mxsxnrsp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbkuhif.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyldevh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwcrbvs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fclentkg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhoebbo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgoibcb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jtzonuqw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tuntuuyd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2happtlop.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdpvedgw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hzzoafgo.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfdncbd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjovefb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgvafsh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgxtrji.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2zoazfjoq.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxysvxxs.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfikhuf.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2duohvpwa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2atnwebir.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzhxkip.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaafsuh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ulrzdlso.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hibixgqf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqplrcca.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmytphye.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgetedf.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oabemnxn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lobngmmz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvftydoo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2huawshhr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbvvuvc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2brpxvzox.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tdudfivq.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iwinavqb.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfmfelu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rruzhtfi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2tsedsozk.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tvtbbjef.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jjjgnjnd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2efkwwmwo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjwfbgy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2pnusfvfu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hyokdoza.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tcggikzy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2feycwtlq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xpmtjcbg.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2heckbwno.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlwvpfd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zfmzidrz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zkybjrag.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xambkdia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2afqamfxx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jqigpamp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hpukvkxh.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wnighgux.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqonkoje.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjvowqg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2myofrfif.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2plqxfzrf.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jichtwai.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jdvqmsrj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qymnuyat.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mvwpohqa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nfiwbuak.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2yuspsnoi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bxbelzrv.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pwvakmvi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2piutyvbf.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjhnugp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzamtqtj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emdwmwss.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2czurwexk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbvbxwv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ljltsdak.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2kakoompl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgvesba.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxmjnxx.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyclcnea.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dmgaabfc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ffdthajo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vfldwxpg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupotasy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2voatdcze.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgwviwj.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aphxqsxa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ynilvqao.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uxjvadri.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2evdvgdvu.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jieilrhy.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2lubtxnua.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wixcqxmu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwnpuxr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlpytvx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxnslie.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrwigmo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hukipcgp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vlgoidhx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qocozucy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zqrmdotz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnlilgz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tebdjdug.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2todcnjza.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ycugtbej.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhwyzpb.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2xowokqdh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezcauvlj.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jmerjyax.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jntgkvkk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ykstbpae.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhfimfh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tgajyrip.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvidvjvd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ajmvdqaa.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkqnkdsm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dehkijfb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lxaupfmk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2neitbsan.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgahigy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2hqftpelp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2dxuzprcb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2krbztldb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qurkzfio.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtiwtkkp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eolfcoay.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2egtsmkus.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2shfkojuu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cslvasly.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkrvhwpe.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvtphako.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qkpyxcdx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uyspsetm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzfgfxq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaanguj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2eiamydpr.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vnclbgsk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjbpipb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2stzqmcbf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yvghefzj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ieqjbaca.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sqoendha.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbsbfdsg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fizndokf.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2absfyfrr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukooxxuz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ktukgtvk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vowsyarb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nghwpjon.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxnyhls.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hotvkjrh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2iqoyeqkq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ksgvsieu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2txgnrvlf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2oickcomv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2vpsuolul.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpiatow.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nbaekfgl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aalkrtye.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mnirvcaf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfalwas.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uczpyoeq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajlhaqwo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qgybekoy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfqwhyh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ermnbknm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxkyuhcl.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zmlqwzir.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2chfcvrql.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ynsjyznc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2xavexzbk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xmeblzmu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2owweflxf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzzjawwm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzfwuqg.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgzsxli.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfckvnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtliaro.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ysslboay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzswtsoc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2buaytvrl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2czvxoqtl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2sawaqltf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwqcrhw.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2iswkshhe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2btsqdjqu.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2vrtfenkw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2jekmwxfl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxanvbi.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2snfwxiec.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jmbulzen.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2umnnhorh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kjkzfkwk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pfewvlno.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2awvqddcc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dkxanlqi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzgfuva.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2mdbdzysm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jranzmuq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wptbxwqf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2naabbimr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qlcvdzxz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2oazzuebc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2izhqkcqq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wytvmcfz.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhtzcvcp.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zagsrybo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdvvhdvs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfipekb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlxxqlc.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dvcxtaoh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfblmgm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqhjruk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrotlqn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2csdzaccy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cniyoqqc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wonuvppg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2isnjhdyw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdktidw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2rsirjzzw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2vbxiwzlq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2lodcrhjp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2chkaoetk.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjlglyt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vshogyqf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kctaqnba.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyaatse.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnfxpxi.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2baasonpl.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvzgivr.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2porfsujc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2eyevebfr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2smtdxvld.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjjywsb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wfhrjqmf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhlarpk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2capixdzr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmpocau.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2pbotmojk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmmmxfpv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2zdxfcyvw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2uslppfof.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wfozbdgx.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bozignfs.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrpptgk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yazejcfc.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2oseryerg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zewduhnj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvuuuwj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaofxzsv.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsbesvj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xypojprf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2coeftsvr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjtbffo.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhzdqaw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xfnxduta.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2epbqiehv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2gqloldqa.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2dylwmrsz.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hmdnarad.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2itirujgo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vrdqsbfx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgbplpr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvlqocwg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gwzdvaoi.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2srofdivx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdthvzt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntcjdvje.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ygniaieu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pmaiixuo.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xyobipic.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2biouuzrb.html


<!-- 参考信息 -->