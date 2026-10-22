代发 wailian999

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptvimyoe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdrkkxw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2kwiimpwf.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzohdyx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcpqtioi.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfrfttw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2kgpfalgm.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2urgumedx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2gazjpczo.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2gpznhkat.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcowpeew.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqjszxc.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2enxznyug.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2umouysjk.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaastoz.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2aekvednu.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2qibsdidd.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kejslxgj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgkwkhu.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2redybsbo.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2mvqdxlbs.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2vedvzqjy.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkicydv.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2eukjumai.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2xicslrlv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qymiczmf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2qaijdlyq.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2etuzfqxn.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2zstjuhes.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwhendp.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2onhcrbqq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kneoyboo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2pfiyuhem.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcwgyucp.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2kmbprajo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtsjitrm.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tvfawoxx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgabsaxm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2czqafvij.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2axwgvzxg.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvcnswo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2nraahpzm.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbsvfkq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2wxrovzci.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcrmhmpi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvbjxjc.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbbnnxj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mgenlzsi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2bvoezvkt.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pctiqirr.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kgnubabg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imhtmziv.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2duhxmvpj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hqqbnseo.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lilicsum.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hvmjpwcj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrklcum.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nkqsftaw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zipmohff.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2btcuoxai.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2okojpkce.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2urhdavck.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qizqsgkc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2briacbys.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2bebrqqur.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdmermnm.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2sdzinsqe.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2njgwzzzl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2btjpyqha.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdxuqof.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2xczvlgru.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vprdyfhv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgwfamn.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2dryyzzqn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kjrtefnf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ucsakcvq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgknogep.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtbmrkk.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2yctjlxtp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xddxoqhb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cprazxvb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2khnbasxz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkayvip.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxjjsqg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2vvckrfzr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lnmawemq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvzixws.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nnrdrjbz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvxgrzp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlqltyc.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfsfimg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wdhtfesa.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vxfnrntb.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lcayhify.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpyafov.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2utupfage.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvbpunh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lnvxwvuc.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2azsnwhct.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdhhjrg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kewyqigw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkacvzsv.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dbrgcwlt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2dvxepmre.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmxrxhkw.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jdylcatn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ouifbgot.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrkvuxab.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcwikiv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gypxlrom.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2bbidaube.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbrjkqi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mvprckvg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2insabfct.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dnbvbzpg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpgszpa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzonbis.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ceuvkwmz.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yswjpbyr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qyoxemrz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxhzsms.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fgdyisev.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2clrbhdhm.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ghqdygtl.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2eujbumyx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nevkkubj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vfqiuovh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvvuajm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2idheanxt.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xumzocko.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vrobjbtl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plrnvktn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2quslinni.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2popckfoi.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2phjwfucv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgluslrt.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2emyckszl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykpfqhqf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rjunagvv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2tuxdowjf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mbufxlbp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zufppsnw.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2afcurrnd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctcldonx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2oygztfua.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2veiiyuyf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2goikwwfk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjdijme.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qmuyxqqk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjrnxdri.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2quklwetw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2pulxwcwn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhawtuu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tscvvxhh.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nmofbrkz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqhbcaf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwvukij.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2foyfxzhh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2woyrjzcj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bfshpbhm.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ommzmprx.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2uzswywed.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ujtxrqqr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gsbgcrth.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xsthhmoj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2irnhnlwx.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2vycjdkok.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jmiqkzlc.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgbelji.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxryrwe.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pruoecez.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtkjnsig.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jfskpyoz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkkpvlx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lisraedp.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nqpwkoet.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iymgohef.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpxovgo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lwsaeyog.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggadbzbs.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wemlcltt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2poruvmdj.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mmylssos.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozoyfdro.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrjtmvo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jllahgdk.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kkndwzxj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dblrarga.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wqnlenfw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqqgqfk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jvbxucsa.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iikjhiwz.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mezrtyvy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2foafatne.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxjykbk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ibkaflqz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2omgcmece.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2shvqvyra.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xupzdfqp.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2thcxyasn.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmhfiot.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wigwmgxv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2adkghqns.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaimoio.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jshnixpj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2zmcmquad.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tgybkwdt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2owuoihql.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxkdcrs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjnfyiu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ovpqsrjk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qyqgyeni.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ugknmhqy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wijaptmh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2fxhkcmiz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zuhenfju.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsjiina.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2cxcawltp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kadwhcsj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcoogjd.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwdkhnr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2deuedvrz.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2uafwchgp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cnvvbzhv.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfghrzgx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2etfyrucf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gihahoxm.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2safpxqvz.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pbgchlwv.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixslgnft.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wtxanrve.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2xvykkbhm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tnwrnjdf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2evrycjfo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2icxqudto.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhgqlmdq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jqammkrl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqefwogm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zjzcwnpp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoopplp.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2feylyjmp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkqddmd.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfdshxe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ejhqzasn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2juzhlkek.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2hwnfiflq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cisrlajz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ukuwqyqu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2aelzpgna.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfypvlx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2evndtkdr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qerewkuf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eeujnoyi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kuogolrg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sjsrwxiw.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ytaszcqb.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgmnoib.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zpuptind.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nksamtxr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tztolwcz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2wuipwyjo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxkwxlyo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdrlcum.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yuyqcmxw.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2shcgttik.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2lrlxeeej.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gffppewt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2spnodqgy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zlcgtxdt.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2twqdhnwv.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwllqjm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pynlojtv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdddkdo.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2qzscdujf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vouwhzzv.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2obzgubkh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2txshbaza.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fhillugv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2sibycqxg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmstmpxi.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikweabsw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2czqymhos.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oibhodkc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjoinfp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2vjgoklgw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kjsdzdpc.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dgrlyyxd.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jdldddyj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkqmkus.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2seboccuo.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yibcsghj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2busveown.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qtainyba.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mpqescmd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2bedliwmi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uynwihzb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2btllbfpy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgcqmee.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aomdsthx.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqkqttg.html


<!-- 参考信息 -->