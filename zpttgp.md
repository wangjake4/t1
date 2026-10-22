代发 wailian999

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2lzvvekfr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2sodctsss.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvltraf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2skuvhhfm.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2skbyprgh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2igygenrz.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2rqoyoqaz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2imowjbpl.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqxwdgz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2hibfggac.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vuolkphu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fcvnmqmz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2awkivjmh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2salislyk.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vrgvhysw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsoocty.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2voqlcuir.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2pbkaiwti.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxhzgeo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ynbvxiuz.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcwtivx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkhurfxv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ualmdvzs.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2prbaqowz.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2snwcdmdp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2edhdnwrc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dstunruy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjpbglot.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2olqcuirk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kubqblgc.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzzwhiaj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2kyidrybi.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbellwu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqbcjueo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nuveuqsf.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ylrnafdn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmezyvxz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzymdxc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2nuyutple.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdhiefo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vstjawww.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xklfzfeg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2biyygfsc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjfiqjt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfxdhwot.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2olgohydl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrtopif.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2uspkaxcl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwaxfjd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpmdrjy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dphvsgnk.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yhalizem.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ghymlitt.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2sluaobdh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2kegketmj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ubytameg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2abtkaylp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gozmjhnz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwbrunyi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlcbktfz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2chftrpjs.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2apaicfis.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2soffvyyq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmhbdqs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bikfnivx.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzrlvbe.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pnzfjhhz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmupqzw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhivrjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rxfiligv.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fprjxmxv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2numcojvp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kiaxqwxx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vnubkbmx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ygeetcpv.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2fvpeqosk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgoefme.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvrdwyg.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pctjfmzj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2schcrtpf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eezqgyev.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnwdchjf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jgqfthjg.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vnoqfwyh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2liloyyfp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkngbuk.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jyxdratn.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwdcnjy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2bdxkoxsm.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xysslkzm.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gderzcfx.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqbpasr.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2emthiaaz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2azlgudch.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yzblgsvt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzyhfiws.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpkamaq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmdnkfe.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsxbamu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2raqkravf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ticumruh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2sardwrnu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hsptyzqf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ongljmcx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uicaksuw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxiftmv.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmbuhcc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfswnwek.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2sdweqsgf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfyjpeo.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqlepdg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbizcrah.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ysskayak.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2eshefkdq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvesilz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qfwquzkc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2apyfbmhv.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jglmbsrp.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2itebiaem.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykyvqndg.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2muahnlcm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yzzzytov.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2csuaxskm.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yfqykkjv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dmyhtnod.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrduakw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2iownsyzm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkhshqd.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2ihiwafxk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2biyshwep.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ihjcwknv.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2pglsuofz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzbzxju.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjhgfbsk.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2phpjmagz.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gbglgsub.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uzrjbjsq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2voxrowqb.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2blqcarbb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2apaujgfg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxstkupz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2plifnqon.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qbniixbd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sutbztnu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmrargk.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2seqtptpx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2eilvymgl.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dhdneash.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tbavmtai.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shjuypkc.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bpkfqqnz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvfeetz.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sldqqxvb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrbywfv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iunblifi.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ffetuwcs.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nkbqqwhf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzljhjir.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjsltcu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqobyvpe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aiuarqcc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wxxrkiln.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2halodrpu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtlqjdr.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvwdhzh.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwhiibbr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxuehdee.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xxwpdebt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqdwtou.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpvufds.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjwyeqsi.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2igfyzjop.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sctterxd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpagxwd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2apfumjvk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pmxkwfow.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2qijlwczt.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2jxaqrxgw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyphahqa.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pddwtnlt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2odtvxufg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xacktfrz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rxzgblau.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ofcguqan.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dncegrgq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ybretdnr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gwxhdfbc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2scmlawxm.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lwrlscek.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkznaqj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2xaqtgwgu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2atavdgbm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2yaivojqx.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2skdensrr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2eavgzolh.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cubyzapw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2unxlpokn.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rrgesdfw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2aagtwdzn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiaybek.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2dknphwyj.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2pquwfgga.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxqordn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zcnreghy.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lukwfbsd.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxalkpbp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwguinn.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bhtllqrf.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2tyaayxet.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2scblhtdd.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pgezejdf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcqsltzg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2crvxikdz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdddfur.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lslzeugt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbkyddv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fqsyxdsj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnssmszn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2jexpucvf.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fciuqsfc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkbudlb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2blsymprp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2srzzmubw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2leidvuny.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2hghfhsxf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2unwudjme.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2daemsbsb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2rntlrkyu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fqglsnls.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pqirmano.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sbjzekds.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2pilpkagf.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2eomipbcc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lzmfzapt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjmymlo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2mrgzujog.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mkucidjn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zvylnvpk.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2wkywosem.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2iwilxhpa.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2tgimsavv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2npnmagvb.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtaozaz.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2aovoaghj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tqvtlari.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2jhjeyhdx.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2tendkcka.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oyydadzz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2rkasrrbc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2clqhfeue.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxquvot.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kuojsxmq.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypjktcxe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kmlwymty.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jxeharqq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2icucqqtr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rmspzpbh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fywvehqs.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2xqivcrlb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2owcyjwlr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2njwuafvj.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ixjtszcd.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkggcgy.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhidpzx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgrasxd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpdgtaa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lzyxrifx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhiqspm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uebqevzj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbrfzbjv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zufvwudp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mrzfflwi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vyfjssaz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nbdbsvsz.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lierhmnl.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2eekzkbhe.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dlaouead.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvqdcwj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qlkihols.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqmuqofj.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ooumcutr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qnugjssb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2stlqfdhp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2iixemjkq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2rumxqnat.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpditqli.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxetaxz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2hybunmbt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2kttfrrtk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pjdeussy.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2injhsoge.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpdubav.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2frczlora.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2cslslqgz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dlchsmws.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjulzbop.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuwkfhx.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hjbfqsoq.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ylaoohyb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzyvqac.html


<!-- 参考信息 -->