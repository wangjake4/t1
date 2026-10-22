代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2htlimona.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2omliptti.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2ibueqhjz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjhmcdi.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2daudmroc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2alohnvof.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2wpprepzj.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ookwudpg.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2mcvfmxtp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhfhyyo.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hwalirsh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrfkjsw.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgcoheg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2kqxegnkl.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiqdfhe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpkmsui.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xifyvnvr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxybjmb.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqxdewx.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2esrzabll.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qadrbshj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2dvarkrru.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgvbhwm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnclxay.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2gpkdujxu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhwuvgw.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rdcvazsf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dakuuloz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcslpbs.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klxenrsz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kznpegwx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2idqpgbya.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2frvzsnbv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2chijgrfw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjjvjtg.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2uoznpied.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lxspeoaq.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zermkxkw.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vqblozuz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2naexajhg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhihjzyg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2apdmokoy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vmwxtgnc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2snrtbqta.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbduwxfi.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xuyygwpg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2rgfrdudm.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfssszo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mktvsqwr.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ggwyjstn.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2svrodiem.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mshmgqkt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrdicqe.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2caehlhat.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kjdhqlup.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pysmbrws.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxlopjn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etakvwjo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cerbdrds.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2llkhnjjk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rtaedxyu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hekdczxz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xwkoutqb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2xcjygicu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ndowlkjt.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wzndajki.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnxzmuq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qjumdadf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmxyawz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2eryeubdz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vsoxuift.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwjmgnak.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmcgsyg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2adcynntu.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dzlodetf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmcadzyg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2foscwpkl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmvsovb.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qxadnirm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvbvlnf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzebynp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqxikawo.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfusrii.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2joneglko.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2yjryqpsl.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvvexvx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2iftuzlxb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhjtypqt.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gxekcmae.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2sufqpbzp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzfwtva.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dmkluool.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpyobrk.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdfgbua.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zrttixqs.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdyqlol.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2opbjkgeq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2krggwsql.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pcqducwg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2badslxkb.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fcqoxgwp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rapcwqet.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2fqnmspik.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wzdtydvw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zohzucdd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdpnalln.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2afksvofd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ovhxceca.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhblmxi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2dznlbmuh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ceqfcrwn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmulzuc.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdzidth.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxuupqf.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2myieshni.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipalojhc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuftmma.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpamnfk.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xdzshqxq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmgxklu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ckmogwdm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jfakyclp.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wftrzytn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ipahidto.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vfnpqjkk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2etwpgqls.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ujmrbhzp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxxrgvg.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2idyciclm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hurequkg.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpkvloe.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2orypsrsw.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2owwiuerz.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2velsfxjl.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2acpbymzq.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2cghgunjn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2keuijzev.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2naaxnzor.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2pbwuapej.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kssxozgn.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jzcjfebe.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2utrqoajz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nwsvkqdl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzpumrq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbwske.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2djwkytym.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nxwflylf.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuvpwlhh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2hthkqqrg.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjueyta.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nxyykkba.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbjwjvct.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjrfnun.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2asnshify.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2utkcsgjo.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzmklyj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pfunirer.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhfjdunr.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lvphwnru.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ctbicwfb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yltazlgt.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrsrogr.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2thumbpiu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnkhrkw.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkoysqy.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfvwsea.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgbpbhbw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sozikxeg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoyzfyu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bgyimnqx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbglwff.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wqmeqxjs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcioymwy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jzzlbnih.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbqidtu.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2yfvfforw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2fydzohmx.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2vqfpxrkt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2zcwojuuy.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2opkkormh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcmsnfnz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rajgsacy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfzlwgm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsndwrh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2clfthjnz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2obywpnhw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2suuigrww.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhtncup.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2llmdbfvc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2jhayftvk.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ogakxbxz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2quenlumv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2xapdonyu.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vluztbsm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2khjyjueg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2itjrrtuo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwebgef.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2vxxabeif.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2eknyhtan.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2aaydpizf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vrhgliha.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdumzwfa.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jyyhksrt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cfbdjwmw.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vyvvdpce.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exasnvxw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqpgfsn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2yqghpogc.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bewgkuvj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqrzxwf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hyuwbugv.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rqaafsgm.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lfgnyglt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dfugwvff.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xnzxodsy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnovpus.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fqmuvine.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjolvyv.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xtjciklj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wjzreejl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xhvmsfhh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpnzkqe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2limqhdef.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbwltyg.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bnrabcbh.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2olvlsfmd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sdyxyejy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2dprongxd.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dgmvyhoz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2xzesniso.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2skuqltfw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmhpaen.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xxzdnphy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxylhkj.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ydujbdik.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kipwcpiy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlaxely.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tzodmoic.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2trcjihrp.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zakbvubv.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xzrflach.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfehvlct.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xallxpxj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvidbxtp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2xpycmcib.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2nhhtwbta.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hsahxdow.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2osyufubu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rdrcounl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmsdzps.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cmghorms.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ednsjxya.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2pggoaglh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbzreji.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uybdandn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgcwjxvk.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zqldmzzp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zynhewtb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ksamjioj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xqmqsfjd.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2yplbdmgg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ypqnvkik.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2jsuqsmgh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2exrcppzv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2iwwozurf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxwhkan.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ixarabei.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqtdrty.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmgsiqy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2disklnof.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhunqwh.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tmnyurcu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nplqerui.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgwakfa.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2kywrcnld.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxlpiel.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2slqjcwqb.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjlxymo.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpjfdpq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcmxhehf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kujvkkkz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cawpeofu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2qxptzlzy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2joixrssy.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2uspnrwgi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajrczewf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jongsfke.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lngltvge.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2oouhwxmp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlqonrq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2vzmpvxvc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2gxlsytoh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlmovpo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xmasbezw.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbpdtps.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2eitsoasw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2thjiuoyo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqugzff.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2hhynvtyy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2wuuqybeg.html


<!-- 参考信息 -->