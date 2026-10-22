代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2jiskopdn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hmrlgpac.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmqqkpn.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2prakggzb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfxeipyq.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2xhsaoula.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2ukztnzuh.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfyhiyj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqgqfxf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2mqgecobe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2egjkcwvs.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vxqmorkr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2pjvftaup.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2weukpdkr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2hhybnyxh.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2iwifgeds.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2smbsoxvo.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhqziba.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2irhzfofe.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ohzurvra.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmrcjrbu.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nfizrrvh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbqzsweo.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2rsabbteh.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2egdtwkmn.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wvjpiriy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2ydykyexz.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xmexmzso.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2cjgcqlbm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkziyjow.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2lgkurxvo.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2gcjxoxbg.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2raosdtkx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dqoukcjq.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2rhinkjod.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dniuxjhl.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pqjyhlnb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgregxso.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2arlztbqk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mezqroji.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2jzafawuk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2diocktif.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stxcvtbc.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nxsrlxbj.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pvllsnyw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vhehfdwu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gtuucrjn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnrwdzg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmgvyfp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgfqysh.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhwqggt.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2prhcevxm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2gnchbziu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jklcabcy.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2extdyhff.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvzgkko.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2jykedoow.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gpunoszo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2iipjquuc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpnxyvsa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsgpojj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wctviczw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhehdrgy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuxacrh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eytlnusf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjewtmq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rryejzuo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vbctllkg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bfkxwacx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2crydsthe.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nwljvmbr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2howruovu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzyaxcnc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsmzsvi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rtawuvoy.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhoseny.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpawrts.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hiozrepl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvayymbr.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dysdjvwy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqoanrq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hbgmvvpt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rdwtuwwg.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbtweud.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlmtjxwd.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ehvqoccr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lokpxteq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jowqnlye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnyaump.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qlszbkam.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vqreeiui.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kornthjs.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ulxfwqtc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2deocvmdg.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeyirep.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uifpddfv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zfnapdmd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2unpzxqar.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhysxbe.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tuktojau.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fmgdkvjz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2nbnoldsm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2milrjwcd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yfctlzmc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dunzdtzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rncrwxqz.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iiccqoeq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcqesmzl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfzuprw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wtjrunjb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdtgnab.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcbfpjs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xsmylduz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcxibql.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vgcdxbug.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmompguf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bjdwjtzu.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fckkxhrq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpxncmj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uyichpfy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dpgnxavf.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qxwiehxn.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tgfqygdy.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wupfopbc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uloyyivn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ausxkfpw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzecbyi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gibncozy.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wvpcucyp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpzumunl.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wmabaefk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaqenis.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fifmtvvy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkuykab.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mwjyallx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2quknshxx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fshncnqk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzsehjf.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mwryzvxa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uujktvvm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2uqacdctt.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqyaktgy.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yibegesl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhfhinw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkuqgcj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxfronj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ztplmrab.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2rgcfcozb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2euqnwrkv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhzharfl.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2enevopkc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbaovzh.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqpxtif.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ujdnmnyo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tawbuhuj.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wisuxgrq.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2buipdwmr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ntczepdj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2favqzhxb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dirhfisd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2catmzekl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jajvfhhg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kgztoxpk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2oktkodts.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mmcxdlws.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzhnejx.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgunsbbk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ypvsgbbx.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrmvuhd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ipeeshuz.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2khfpawvh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2iodmiehz.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyhlhai.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrgfiti.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cygivxcr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgvwmxe.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2auomrdxa.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbnzzrn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wmspcvub.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywzkrvyp.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hcvuswwo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjotwfij.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2crkwvwnj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2objhloij.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uguzhgei.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcwtqxap.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ujromuqu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tggarpxj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpjwyzf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kchwbsao.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xmfmsnfk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2viotgyxp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjmofrw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bvbgfkij.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzxntie.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ezkhkwoa.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zekdttmr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2askmbyhs.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ngjdnmht.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tkftghmn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rchjvmkq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ppogyqgb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaikrmk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wprxouir.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uebvdbnq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbswmrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2aldzcwjt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2krumrari.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2gahkcblp.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aiyruleg.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwautln.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2mqrsdulv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2idetwoid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxvlrsv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2yrnfwvnp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sqpqgakh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhxvcgo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqufrze.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwbgslh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rylukcbc.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2luhdholm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sadzqeml.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yutroqeb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaxzvhw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlyamue.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2owisscfk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ulkeltaj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wkjneeeu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfdaogz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2yvallzwu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxxuzgq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qdqlmofx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pmtjxwqr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vntxaxjr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2oqscmcdp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2mygfoaeq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2giejvfer.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfsayeu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tbssinaq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrdmnlh.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgyjkwv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dmccxarm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xikcbdrn.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrudfide.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2pihxfojj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cicbzxwi.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iatvfito.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2faptqval.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjjkucm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2nltcpwpq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fxeirlka.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bumwrtvy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqveqsx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbvhwece.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ghwhbwxa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2firvalev.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2kpwgkjws.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2utimzdhc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zfrxtxgn.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzagoqw.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ivccrxjv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gnkqqzkx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2heiamcxx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqmqdzv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmbdgqe.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2quwdlsxv.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zlbfwihx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvudbwit.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2igfafmig.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmvjzpg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gcnopjdr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fsryuwzy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwxzfpg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfktwfm.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjcfcbr.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2quyfibjd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fdnaffbm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2gchgxuyl.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ntdgoggw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2eietokmd.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpvhueh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wxveabwg.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfodoil.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqbidtx.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfipvxcf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzflozmq.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fwowonty.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ntjaoavd.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2puouskhl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jdrpqopq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2kdzedply.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcvdzse.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2huycafps.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhufqrk.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zvagwpxp.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvgzyrdt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2kpybuukm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2btutrhep.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2kszgfcdm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgcfieq.html


<!-- 参考信息 -->