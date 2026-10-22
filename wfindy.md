代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2chktgxxs.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qdefxwot.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2drrstqjm.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkyqajj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2prlfurmk.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2frnvecmo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2gucpifer.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eggahelm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ebsomxzg.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ejfrxvzo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrhbhka.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2wmnolywq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2edxprzze.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pzlrwpmr.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsehzmdr.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2yzogaljq.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyqjzcqd.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2swkskbpa.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bparvrna.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjzrvfk.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvpzbse.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2knagitvz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2hfaiisjr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2dedudotj.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2lpttetba.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyrifai.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qskqouvr.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owxzribs.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2etvberkw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvrvfvlc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evuzckkq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2rtuqswel.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2richnrfw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnsqhba.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjfsovi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nroqsqnb.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2cppsqecx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravwkvgw.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kzlhuxup.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mukfjsbs.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2emzyvmwl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgsrkvsi.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhkqnus.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkgieip.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kayluahx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2cvumhegx.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jnztrdnq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2nnoufibw.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqarisym.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cdnmtzjx.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqhddyf.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjgjfxh.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xacodtib.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecbomwvr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2htiypued.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2csgbsbjk.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2shpnllsc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hsmfbldi.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ivexplik.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqnlmwr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoyovmp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhjaelr.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wsrbxory.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbehndkk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2txicrfbh.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nhnvpzbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mhqozwjg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wbzkchyp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2uladtlsu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2degdggcb.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqaapfk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2xexxzkzp.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rkqzekss.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2smonevir.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2kczdslbw.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2otehoywu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqoolmg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjqscwz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nwdzxhge.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2peoeaovs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoggcwo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zuasvimu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zjxnjfsz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xksbntwy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2joulaudm.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2exxtyjoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2zozmxntd.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vkagpave.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2szpkzzqu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xxydczdt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vgmfbiew.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pxfjbafd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvuknksq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncinkqwx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hypvfvho.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hnonljgg.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvflnje.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kijvwxjl.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ahtikwsd.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2evrjfiyg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vwbqeljg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2smrpkvol.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jsdofwsc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmuootzz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ycdlgdys.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhycnrlt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ubmgwers.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2neafbrgn.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dcdavczd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwlwtdj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2crjpyrwd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiahoxrg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rygrablw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwetpab.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xyqqrrpr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gngrxcwm.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2zygedfaw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2abwhixoo.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2urkfvslk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tilkrrln.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2egtmocjx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kuvjsnuq.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvatjfx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ixfjfyxk.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lfkrmsqx.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ozszofrf.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hqfiugya.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2uudtiykp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwjscrh.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxgezfst.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2exjjcvcj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2yhykfdvt.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyprzwk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kbggihni.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cndjxnwo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ktsnjnrz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aavqaevn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2oydrobgn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rzphuvjk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptppounm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vaefaojo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2psgmqrad.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uyhsjmsi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2kylemwmi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2tnfmwkhh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2seqluywp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmtjuvk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkdiajn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2etosgmij.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2folupvzb.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2honjjwnl.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2yldjiott.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rvobpzuh.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2propzups.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2krlathlr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2stmknhdx.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpiqymm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdaansu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdnspeh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dnyjavpe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ganlohip.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdptszw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2liyyzgno.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcdqsgu.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdswocl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxueipwr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2srkeokwh.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xwperdiu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vagesxlu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qphycipm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cfgposuj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qqzevhzv.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lejcwnke.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kbuyjpjz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kbyigggn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyxjvqb.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2erezelft.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbynqixt.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2imtxkjhw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wsnsqjfj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kwwnsemp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oaouzqqf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wdssmloj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnmsxtiu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwugeue.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjvqpqzb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2wygwgiux.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpzvwukl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2duybhnhw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymgrzzbp.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dmbqbwvq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2poeccdlj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxtxpsb.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixnwcp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qylsynhp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uwiryvpq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhrjebs.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2aecjmnmz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tsmvhuix.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hfzpcisv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nutnstbh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hdoiqpxl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2bumpbkle.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsxwluy.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmajkurd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmqjssj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvnwzgy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gphowydy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdaznew.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eqaauoot.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnziasvw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2revxegzj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2igqlmdqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sigjmlyo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qllsbbna.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pchwrpun.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2llcinskt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2sghskngo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyktcey.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lyumdthf.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpoiruz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2mxqxprfa.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxcyyck.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cqhvoiqt.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhnfdbr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oizbgdpx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vusflzbn.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2qhujfmcz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bkooufsn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2oceddhmt.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mlerlntc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2xlsflxry.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2grselgav.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2umrysjqs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vbgoonls.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2poyjlzxr.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ruoxcupr.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzozypmq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2htpgzphn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgenlztn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mfjnyjwk.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gillgdzq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jlnjvvdl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2zukrpeat.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2fmztspln.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2hwutykez.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2usfdwttj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2bueilteo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2bnuyuyib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfbgcwug.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ikcvywkk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qxltegas.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cddrbpzv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mlhtylol.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmlcrow.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2cygjgogv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rebsgufr.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxzdnxo.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2rzunynod.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnlhjlx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htkedoug.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2iaucvrrl.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ibimmksj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlyqmspu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lnoooznt.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2phylnzil.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2whequxcn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2bgoqvgjs.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2blwxkmaj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2urtjdhmq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtytbzx.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgdpjbn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hdurtyww.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2oypabnks.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gpubpozx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2inaglvpc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dowzbabu.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2epctpdiv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2gfiyocqw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tuvmwqsw.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpjmazl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ccphczhv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2pocukpqy.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmkwyxom.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qzeqeilp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbjirve.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fsyizyig.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrfgihlq.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2qwsgfjhd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzhvojj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvlhzfk.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2injrwilv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oypfnsmi.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fosfryzb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bifvmxyy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpfzdud.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2nzazkmqo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uhmxurqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jrtiqgvk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzwgplt.html


<!-- 参考信息 -->