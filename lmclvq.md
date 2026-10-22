代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2mibwpkwb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2bexxaokc.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2kksvykms.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvzejoa.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpkutqm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yseczetm.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2iocnctcf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2yvtsluya.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbgiczw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2dcscpsuu.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ibouczwb.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wjprroht.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ycklbjow.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2vdackglu.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvitizo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gycohnsz.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvgyvlje.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2kxxictnt.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wisextub.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2rwaslowd.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2jffnwyvl.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjrnumk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ufradldl.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alyzcyqa.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2djpxlaub.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnwsprb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfhxojv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cskvqxdm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqrvxaw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtbcurfj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zltqoopk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmjjqpm.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrcxcawj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2abcghsmf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2utawahpr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qcckgwxw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzgdjpm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxzijlr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ayopjvku.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2duemmtwl.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydmpfbkc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebjkteji.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2jipxqrmm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cnddxbhw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgidwwwd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yvnhhdmn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mfncxncj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ksssospm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrxdber.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsqqfcw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrqetqe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2sjozlzka.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cufbzhvv.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2nzchmvtz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijpcmiiq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2adddpzpu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2utwepfid.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmgecmr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2lapzelcg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyndqlmw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ocpwydud.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pkmznmhs.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2euorqvmd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2lhyzbkme.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tpifompr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wgljjuoq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lyfziwbw.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2awwblapq.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnpukfj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2uppvbuvs.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2plmyxopi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmedyid.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yvhujdgu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgnukyu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ogkxhbjg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2buytdshc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qjimwrky.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2sinadbrh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2galysgaa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvjfpfvt.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xccokgpw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2oujipvpd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qvxndnvw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kgkrrkba.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2roykuahv.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyxhrsus.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2niumilow.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqnazdox.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2hbazjmkx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpdrpyxi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrfywgg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfphmqnj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bjcjkgtu.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fmrsrkpi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uafirlhv.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2pvydeuzq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2reuzvyhp.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2klzkvwjf.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2elyebwix.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytwavlbf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pksdvuzc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2htaxwsej.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmbkqja.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iabdhbtn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpsoziq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2joizchpa.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2wbrjgonx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfwglzd.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nphwvgih.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhfpuvu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ncknabov.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gqxrpzgw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gylcduuv.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvfvatxg.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xmogjtte.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyuwztx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2jnjkpynv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2qizieltw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlwrhbd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqkvdrwe.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvdtzor.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtkacyz.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsoqwxs.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2iacabzja.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmizugp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2msmmhajt.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpibypq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpqkjvd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2dphgducm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdqbukn.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2omjhhgzq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2snfdoali.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2iycrwhka.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfilcju.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2iytegzja.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ujpfophl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hvywgsac.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtgjchy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pfwkbuql.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2egwelvxh.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjtycjtb.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgrlosb.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aiplqgup.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2stovdvqp.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzuajxd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpwdpfqr.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2floyzzwl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyckpshr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xovyawqj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvcollq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsixukg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfyifgha.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgwnxvq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsrnyum.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gmliagfx.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmqvilr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwcgzixo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hngpsvfb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmpwxwz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2xacvuueh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppwzybgp.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjtwlgw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2caoctlqk.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdqgbroh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cnloocig.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cwuskkym.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyjwhxw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hfbodysq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyfowhah.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yunbkwqt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2basaovji.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dygtvsnd.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uymjapoo.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wetgwalm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lemriqjr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2brwloxkb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oupuhtmn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbjyham.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dsblaqjw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2agfwfrrr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqjqivdg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rlqndfkq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2scapwyqq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zlxqfdjc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2apipdpwn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2vllafloi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhjqczl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vxzmhbdm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkfsght.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gawiuwqn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ypfckugr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ssstkwlb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2avpdexps.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tkddokay.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2peczywdj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2wxqksqfp.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2srmszdfa.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkhbvyr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gxscqjsi.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2njhebmve.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2okkptpoj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvftvim.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlgzcpk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dyfggwrv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tcfuxhqq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcleuah.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lnqksfke.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2abfjmvtz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmmiycm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqiywxrg.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfjnnhc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptujlrwl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhacqkh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2nemwwdns.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2txpmqsbz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vonewpfu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2udektjhw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwohqoo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2okcxjggv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tfhsaznl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2awijdajw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwkjiwn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2giomlvob.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ywpgaxhg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rsqujfgl.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bynxzsfg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ngprarzl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2cdzqlzii.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rcvphftv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsssdzo.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzzymex.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2iyfznood.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2shahrpqo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqewczes.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mdvcuczp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2weaechis.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2btzagfsr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2bnmqyavx.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmnwhcv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxlkbeq.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2biblpjpj.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eankrgzn.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gxqtmyyb.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xrpgdbom.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2bcsksckl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cbgbmyvn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbfyjkd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2pumcgmai.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dewknjog.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zazpmske.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2omwyevwl.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2inbgkedt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2goeamgsd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnbrqea.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bmislfzq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ycuvlsia.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jdukekbs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cakctbrz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2nxnjzdse.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2zyurfvbb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dltovnjh.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzngoke.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nkhdezvm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2chqrfrbh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zakoonzw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2msodkswi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ewakcpph.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdphphl.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlbhwap.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2onubuuis.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpnwdok.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwjjmdqx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gmsvpclt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwzqwtvu.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nbxjusos.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkfnhxs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ahosmjkn.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gggloaar.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jvihztdp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbfxzqyd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mnqjiuit.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2oiizxgsf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2rzyidxrq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzuykup.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvgcdbj.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hgydvisy.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fysfozdv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2iohqbazy.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2szfsptoj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2eqyzuimw.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gacoiwmg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vilvpkxa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfrjzjv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2bpewzxyi.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pwdcuupy.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmisgi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lusggigt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bqsezfbj.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dduxleid.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngbigrgz.html


<!-- 参考信息 -->