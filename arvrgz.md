代发 wailian999

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyhmftsv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wohpoguk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2zijzfewj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrzcrcb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2qsairwzt.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2hbykqnlr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaouatcv.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2dbuamrgx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2vbdosqqf.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbmxgif.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpoklemb.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jppcrvhj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2rfwaukin.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2eynhzqpl.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2iwhdxkyl.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2vdgjwcmz.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgzisycp.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nhqvysys.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2adzbjdbq.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yofmigee.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2osjsuced.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkkikpm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtmwtgs.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2pdumexvv.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qliwaklv.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qlblztmm.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2fehjcwax.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hllftkug.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xszqbtwe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uqrzdisv.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qwezivvc.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2lqgcxlut.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2ltajafsb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2blpzxkda.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2gujuitxl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhzyopp.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2hbovtblq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2stlyjmad.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2uqccdtvn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ftmxdhyi.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2ibqhqlsb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2djhbiije.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gphitpeq.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vigiyvuy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eyeauqeq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2mmibtbrr.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vxienqok.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbqiarmf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ujelorpv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtuisdy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gaustlss.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwhtkxl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mlpqauwa.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghawsrfr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wbnwssru.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nihsdfcm.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vixchscm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vgtbknpt.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hsimzcfw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksvqkvzx.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pkamnfzj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eximywnd.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hphnoews.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2wzhdecqp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzvcruli.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dviqhmdd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ahbhkjfl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2eahveoix.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwrmugdm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2muzhhmym.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2jfyuxiuw.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2seuoccxc.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvmwugkv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yftphsdo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbbqjxa.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2umlxvrpr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmybdowo.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ionoxvrc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lgamrpuv.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhvkixw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnffecq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iebngufb.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dnezpjvh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mfwbyubu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pugljnqk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xuzwnkua.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2tvinwwyx.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcxfzvb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2csvlhois.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2emqxppps.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2etahpsiy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhgopvwk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmcdmna.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gnzgiarl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzyzqnw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2pqygadyf.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2slpomixd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkclcll.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2cjulnpsx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlkkuti.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2biiytlal.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2alrggjch.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bprpzsvp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjbhqphr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yphabprh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxgtyyq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdloscs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xzkjqmnw.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kadzojli.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wddxhfnr.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xufyncdz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2laomuwrh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2sponcnzg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2awycjwng.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hntprgar.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hywafohe.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jhcbgplw.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkoylohy.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2azyupeoo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrzuwnq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gclqmmef.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcmxdbm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpgtugjv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvwlkkbw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvbtdko.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyorvoi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fftecvmp.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeaaehe.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2cseghkkk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvztecqj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcjdxjw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucvilmdp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rblxhwsb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsijzbid.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kncmiwfa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xayruzwg.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2txfuxykd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkjhzcd.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2crriojqi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhkwrlt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ihofgocz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2avhwztut.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2gumwtkzv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssymnzun.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yykawnbs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxmvuli.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2huzzcufg.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wtgeiteb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dcxfndok.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdjxbumh.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjrcnnx.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dymsfdpx.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnvymau.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bakxjyro.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ivvxvbwe.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2eclwysyk.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2rueywvcv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjmoltp.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2efadxdnn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2stpcsjtu.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sujmkfny.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zelsegsd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wcimgamo.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jgwyqykv.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2okxxevsr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbylkmr.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hrsqsjpc.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzjddpsc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2whrgncas.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2btpzzoxu.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aoyujabw.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rbscuhjw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjtyeev.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xqxhciqp.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkadsnc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2iexqkisn.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2octvsqke.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzxfwzn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpvknnx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2davhfaac.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mweokuaj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ysihgoak.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgmqxgx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whrrgipr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2hzfjgzws.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhpnjtl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szckpnod.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ioindlwj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vbcqznbn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2urjwbeyy.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tjgkqdza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2oybbyjtm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qperbckc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kacfvkrh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwrfpwii.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhvxzri.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eadovtfg.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmzvkkkc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cwenyvng.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ljskmway.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2odefjksl.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2opskrqzr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbohzsmy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2yceiihyk.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqqwwpq.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rsxiovrz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhoohoi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2czbnoeug.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdpbavy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wtftyiyi.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvsxfqur.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2plwcgpxa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxuthvht.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhhvqkgx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2xylsfiay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdaqucjf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kdyiyuhl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2uytfbyaw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ujhiewru.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nngkoiha.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2hisdrjjv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtxhhbh.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fgeycajb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2xuybwvhv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2uikifzhs.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvvaxij.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrbgitc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vbphazfi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ynykizqa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2iemvxabb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2czrcbdqb.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ligenexw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rdyhbrrv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxktnbwi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sxfcckdc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2knlovkhf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pylzeash.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2irpjdoci.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yqvlafwy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvetwyu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wzneiqhl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsonsdli.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cubxqfuu.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aomcvuov.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hchuiuje.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cotroxrs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzyblmt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uixzpgbt.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fynajmpr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfkpwism.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2qypkxzmj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2muqtrgqi.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rryrjylo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2arlofirn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2iemadrtw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwucqafc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hghcguof.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2brlorczc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2iupiisny.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2yglrdalq.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sotjljuc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bqwuxqqs.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jrmhzrdu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuwequr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2hefveify.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2yntjissd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2rxotrhhx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2llozvxfy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2soiaitla.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2crjpgkwq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2cfvqydug.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2dfxenhkj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2lrktuhdt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2wkiaacpl.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xitirtgk.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeursaq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dfkmenih.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2llsihwhi.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zslbrnse.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgdllcr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ldxghhgr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2terhdkyv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gimyfnnd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2evqsmaal.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kgeddxlf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hatydxwg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqcmsbi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtxfozs.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rzacvajj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rszgrtsl.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zndfoaqp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ynicrgyx.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwsuvfm.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxomjpg.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2wpjlnizr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lroqwrum.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ppcxhyxl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2gzyaqggm.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pbecrzcp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2eyspaptm.html


<!-- 参考信息 -->