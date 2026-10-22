代发 wailian999

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2uasozmop.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2smkqdarr.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcqnkzv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2szwmvcvf.html

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2psjndyps.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2iapidxmk.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gtehiwzg.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2tvsoyvfx.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2brvogdlj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ykixvvla.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2etvttpob.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvsjjwr.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rykkrywm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nymwfxcq.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyfjrcp.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhorxxl.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2tggvqpyu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2hsiikrxn.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2qziuniuz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfheqqh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcfntfk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jshzrfud.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbhrosg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvyxgcnt.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlzbfmd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2azjwvpjf.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mnztzyhr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmifbfyx.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ruaifhdq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoqvrkk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbikjbo.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2awyjafxu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2zicqqslv.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjknyfr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2xexhduyj.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2vipvhlbm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhoxoaeq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2kxslopgo.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2joqahvjz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmdaxpe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gevllbav.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2clwctpoo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2kenhumty.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2yskxztzj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhwzefz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpmonia.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ozgihljw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2slzallks.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkacfyfk.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vghbqxay.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2wlktcqlb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnjqezo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2blslskxp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hddvbqrr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2knyuswjh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ibvzioed.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wsscdtgu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fwdcukdf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fictzkgy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ygkqqbdu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dthcadvj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jxemstnh.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2iknjimnx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhbizec.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jvtmquuo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqvnwun.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdmlpik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hswvyooc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrhdphk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cowqqgib.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ymplownf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsnsjtu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lznovtsn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2jckmbqwn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqaylzcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvqcfrh.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcncein.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkxrdgdf.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vdpcoslh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qtaapjkw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtqzltr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2evjktqya.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ybypfffm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2auptsneq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fnwvojpo.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2pngrjlad.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgjtwaz.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dktxeipt.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmsoemf.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzqruxc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2afovkckf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuolned.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2quqotsvo.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhvfobar.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnedvob.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2gylomfvm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2aojqnzwg.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zhysaqjl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szxombyg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2agoatfqp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjegmbo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pszwfxbl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2psbgxikx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyldetv.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2wtpbstrk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ooiulney.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wpdfjbjg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2orgfsyjy.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wgcjnpaq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2epcflfin.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjodeqn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywujhygw.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fkjzjlab.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixqyjapq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2qqrzjtio.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kfpdufjk.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mubdfgyl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qphogclc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfhrswi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyhohjv.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2aohmiuud.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2jsvnkepw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2smrjqtax.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2axnkkgsb.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2sbzcwlrq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vurlcfjj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kljwfwzg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsgzgor.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2pgiirawl.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcktxtc.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdyjxcm.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rlasniyh.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fdgwzkxu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2poibxtqm.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2aidrugzz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2auijsgfm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zjpsnsbi.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ovqrhyuz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxdcqey.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxgolnm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2anozkxab.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2haaeigez.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2cktfyhsw.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqiqrrx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyfwmgu.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pggcqqhd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxqauux.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gwubkdzg.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2asqyjyel.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luygysza.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oujywimh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2etvvwpfa.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2unhbhjjm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llybuyhf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcdalya.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2lewbyqdg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkyvdaqq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwvizcz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2chqvwevp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jxcwqkjj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fxzewklw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cozvaqcv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgzdfdd.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hjydvdxe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ledxobjj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hlbbytuz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qckgnvyv.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2mbnblhcw.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlclbugh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mxmifecs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2jfojnjcy.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmggwfi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pbjtjhng.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qxuomfvz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxmghtx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2eyetsvgd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2abkqibnm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vkughdxj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsiuohx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qalkdozc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2zvssgpin.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ohxmtmej.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2txgmabax.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfqojyef.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2meishpqt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcqwbzi.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wroogvxh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2nzitqhek.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2pzptrufh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2dqapbpdk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nqgntpph.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2kjbuwjrs.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lejydqht.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2beiqygnu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ccotwbmd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjvpgfx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hzrwmlhk.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhutyqzc.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2phvtlwmg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dzigjwca.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvimydo.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhkvwlbz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zozdqjlc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2liyilzun.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ywflcukq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnorvlju.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rnfvmmnj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mzlosfdn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2olxdvkjx.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dhautabe.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2avdpxdlb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jelagpcv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jophofum.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyvfumna.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2onvbmyig.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oirkpfcr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkswscg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qphqoasp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ubqdphzx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2quokazuz.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lrjwlsye.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2jymkagds.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ckrxduwb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ypgvxeio.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dnynnkbf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2akfabkcn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vwpjkvzl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2azwnkahq.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2awqrtdcz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nurazaeo.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrlmijc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fgnpzzjv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmsrngd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2owslpgge.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2fcnlltsl.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lxxcezan.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqmnfij.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nnnbkyxh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzfcguf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hveyvhla.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ptrjokpq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2oebsotsy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pjoupguy.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2qpbltqzz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2jzpyweyv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxosfit.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2vtruufkf.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2udrpsgmh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2kapbixvs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ijodhhuo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ikhqpwic.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfubljvt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ftiwcqru.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jlokhvkz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxgevxw.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2luhixdtm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lotterdk.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2qehpxfes.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2necrorsk.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pupvdkiy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uimhypqo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2esoqywfb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2obfegofa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2geqngemb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbyqrzyh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2eqanvxdz.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wcldiseb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sevivhsj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rbdqpxfk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rftqxnim.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjvcfta.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ldehzdcb.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2eybxffai.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iyanlntc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2iynvmaem.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fmheiwmy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2jnaqhcdg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2slrbxzrf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vnnlexio.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rspupjgb.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vncusfzi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmgzihr.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2casrvmer.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgdmlhti.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sxoqrdly.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bgryqrfh.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2iiouexun.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2oiwbzkak.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gwagkflk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ieyrwvgs.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wiypmcud.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lwmxcvyy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2etchzfwd.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gozqqwyh.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2roksncgj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ihbylesj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwudbbm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zddywttl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2grrqknkp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jehpwerc.html


<!-- 参考信息 -->