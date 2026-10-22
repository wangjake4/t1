代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzsjjdok.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvxkwmf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qmtkrerk.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2wuceiqwg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2aweidhbn.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2snhoerxa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2oomwwtfj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bxxcwcvy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ncithkrr.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ucosiqqt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkslwyfg.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxcxyry.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmvljff.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2kruhonmr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgpjjpmy.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2sisrdgxo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2esadcmlg.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2gzchwnoy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jvknaeli.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxuybws.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhvuqcbg.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoquxay.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2lxivzfax.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2cjyyoqdz.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2yyyhfzef.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2klemqymx.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2lermcdfj.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nkawoqed.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2duvxduqz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2moxfoqfh.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yfbqwuwu.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2qzxahhah.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2hrackwxz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mumqassf.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2wltniwnq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqrmtbv.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrrvvw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2aleqvqwp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kspvkdrg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhbgcbd.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2iatejtwo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2okxovrlq.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbjzduy.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2kuwjrzuk.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eilctfyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnjlwjs.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ntxzexok.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjlahyde.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqayjep.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxkwpet.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfrxaoo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2wunotbwa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2fiueiivd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjsquja.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzjtnkc.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfpdcpz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2hncfmbge.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xccympnm.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwmbozh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pefuwbel.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtuhgwd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzistax.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2asftlaal.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ryjdgtxl.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmghemu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdpvwdu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mskuhiqu.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vcasrcsf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dhvhhjhs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdfeqsf.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjdhoalu.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2gqrpvpqk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2igimdecl.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmabyuc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnxoygr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2acbnmsgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nroytrvg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mjgvddju.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2woidqadw.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2tqnoygkh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqfmbckh.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2otaabqap.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2iujqmvmi.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kmetsmed.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2roavxdnm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcclhde.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cibvzmeg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2rsudbuyv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2suzsenvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mkbxjbqt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cpjekfyq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uywmjpvu.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxixrwyg.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgbugqv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhbyqlz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzdqeot.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2awclvghw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjcvekf.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lhlturkd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hakzgeul.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uydsnkfc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pojrgafd.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zktvkmws.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fcflphqr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lfaijdes.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpknmpuw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcevpyl.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mjvngycb.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtyxvyp.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2niuwmwdx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtltcgxm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eztdshjk.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2hqjmyosv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrrdzsll.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxlinty.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwvhpdvd.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2taskxifo.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dfsvdstc.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ajzvdehf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpziraz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2smkycxuv.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdeyibqb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzgydlbj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kibzgfab.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzxofouc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eqymlpoy.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lymgitbd.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdilczuh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvkdzdo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdhadnk.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyhnpxo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqzagdv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2boscmync.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rufozpiz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mfxdgeav.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgjveek.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjaetkji.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbegsog.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2yjilzbdw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmcycodx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlruldm.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dmacuijv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bzdxesuw.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oirsrvdt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2llezblpw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iagemzww.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwgdwsk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2znbwkshn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvpjul.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2twmgvkjt.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmsxhzd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bbiipqpp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gdgbnogn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxhvkzt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rkawigpf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2drwgszak.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ufontnvj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2yijaldvv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmurvnai.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2amsgacae.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2lridmdbo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2feuekhez.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqzfnzk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrtggfc.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2eefrhyne.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbluxsyg.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pkijyzxv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2votgauwe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2htxzcdwu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxfsimfo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2imtovnmj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiejbfk.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2glqkzyiw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnrrdxw.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2myhfagel.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iiqppkgx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2glizkxgy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkbgoese.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfamcugr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjtyxhcq.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2erwkmpnd.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bufmslkw.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qidpxhlp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsqhbmq.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxgxfzn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpurzav.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2coosaemd.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2clmnfsqb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gzguciln.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2umfgkebv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmebxvk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzkqehwr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tqjkvcsj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlsnspp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qkmuavie.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2huiwmahh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hopitxvp.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbktxcjq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qygmttrs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ehrzlndr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqdvmbp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2piwbeyqq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwiwizt.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iyvbgrax.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ulbtazmv.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2grtlqkzh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cecdrwmo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvezqws.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2znyzpkoc.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2owysyqrv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxfsvye.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvltwo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2xujuaduu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rhrcbvgc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xivtitec.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtsrsop.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aepqctci.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bnifyyaz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxodwpm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2waiqstnk.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ibadyezh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaabroi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfljfxd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rowlipak.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrpxokz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tpdrkppf.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rmfqnnrn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlgavbm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnvtjmy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jkmwlbkh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ditovykn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vewvjvqn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2naupakhz.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2bllwyzno.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ompuhmoh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnsqwyx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dphboxif.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyueuob.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fkljjpoq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtpcfmk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2waqxwvtj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzclavih.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pyadiqpt.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgitydc.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2jwiahbng.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fcwxqbks.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2dsjterie.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bkqcgpzt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmirxiu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2blknsyvs.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2genpljgb.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rnktobjp.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2tfybtcag.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2egexhiaw.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpoxmyc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzkaczfq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2nwxlzxcs.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yihipujh.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2loenerfy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2auwfmqdu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gncpanwx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmizacy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2demlrfue.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouovgvbz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bfpxfqkq.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyzqgegu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2cdncdnmm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rosymdmc.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bsvtpahf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2aahjoupz.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vpuaahca.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxczotb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiebvxz.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2awyqopve.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbrxbye.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yglzndvs.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fmygybhh.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmfsnhh.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2proasigg.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2omkemjig.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2pohgxnur.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2shxclure.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lcqfvawp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzpwjle.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rljdxmbd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsaplkdo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2tbilmrvt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqytdmzl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oetwyptd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jujxjrgd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xroxytfu.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2cichqoay.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yjabhyom.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2pgjgebkr.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2epiqdtem.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcooqfm.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjnxjib.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2stiookqw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgsomqn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkdpvpgu.html


<!-- 参考信息 -->