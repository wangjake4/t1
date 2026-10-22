代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpyqebb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2jqbyhejb.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjdloxz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdgsruny.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ctgewwgl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ojuwnzso.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pepkoxsd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tplxhvzi.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2uupsdmxc.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfyywvc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2fqcqelvb.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uvwqzlro.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2djhlrkbw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcavizy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2efztyduj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dnkznjsy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qnghranw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgxadqss.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndcqrcxn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dizdgywj.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbzwhsku.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dktockoa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2snvrskpq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2kodjxjvr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxtpyoo.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2umzcyrzj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tcifnqwv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2berruytx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2axrurdlu.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vkatqiub.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdqjrmir.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ievpkqpb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlbvuqp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nvqcllwx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xawggbmn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvrgkqu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2seklmyxb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ujxyiuew.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxjlhmvu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pbctlvcy.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2smfdoomu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwrkfpi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2gjvdjhdg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkysylk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2igvoyegp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xpijghhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdiltykp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iewxcuzx.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmxmdfv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zdeuptff.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2susbwkxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwypazp.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tohrjbdz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2eywaoyjz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcwzssc.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2nnufmpgp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2trpzpmxx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2asrjkbys.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jesfgtly.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2uobtcqig.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2gkywjyeq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2buwmfdqw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dajqocwu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdznrvr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2swfpvoaf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqxdtvp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdifalli.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwvewrev.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqnzhxpb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsckerhz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qavjnekm.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wysuhwgl.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2sqtqahjn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vihyqnan.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbxhfaq.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2oflfachv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lfefkbdr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzsrywsw.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hxiuxpzc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuteopc.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2sekikpie.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fdldqexp.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2askyrmxc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xbijjfog.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2xufyehon.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvwfnnu.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jiuaskwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsutzgc.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gopievmi.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2kltjdaoy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vieyvorq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vuncfhpd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ogsxqpls.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2soiyzmui.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2zvykmfke.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpzhrml.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tnczyibn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2iqqtbwan.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dyaueqqb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2winbgcdw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcjvooi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjiyajj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2yxsaeiku.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sewcpzfr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gvekbzps.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfypoodz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2euoqjbos.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmkaopr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tbpbdfwr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzqwchm.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yynyfzhl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gddkptgy.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcqmsex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgcverk.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ijfpnyqo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2mxbqzgcm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjffcixk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpmxeqq.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tycthszc.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2qqckpzit.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2paypoiyy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2apfdnxtt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hzwzrvbk.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2alwgvwce.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2holgqamn.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xubebpjg.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2whdmrtqm.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2kncgggfy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kzbmdpmf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2taoqgodh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsryxho.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2soywjipd.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zcdzpbvx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bzyhayjn.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2lieqilta.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqitolg.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rxbnijjo.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyevdlvo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2btbkajde.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2luovgtof.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2pcttqasy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvfpltw.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2szkfrjqh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2zbcfdfze.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xqswbgsk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggfztlxa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ciabbpwc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2onezhtqu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcpqygh.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2aylhbojv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dqhygxhb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cylvjoqh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hrrtyyne.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lxugdhyr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kiiulqsa.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqhapva.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbmosqrc.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cgoeqkbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uisxwddu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wxjmconv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2nhxqbsol.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rvfalwhn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2beeowmkt.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nougrmld.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zhotdudb.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qcnexycn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnzimcv.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2jjoxjmut.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfjibkh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzyjjsh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ikmhkcps.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2esegdqwe.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ztblrhbl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bfvjehju.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eyhtxhrg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wngybiip.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2llhfewiz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vntfhfjy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tcwzpnet.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ejwxzxla.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2fqkacymm.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rewbkgap.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2chzwdlly.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2vfohesxe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2wuexeukx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrjbbql.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jeyheurq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrmuxrx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2lbobeina.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfosptqn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vwliqklz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qyyjarmv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2egmnjkci.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sxhimava.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qxganvel.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rudevubw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzsvgfh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2kxlqzrar.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoqwnmp.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsstgmg.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wkpcbrxa.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2iudkdxfr.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vmdgasim.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oickrlpa.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vxgyaafo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2eadhvihn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiirwsr.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wghqaeqb.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2sitkpyxo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2huhrxsiz.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2myjuqtjq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2urccgtxs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2asrsspzj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2iiymchey.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2xqlpfubb.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxlgpbs.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xlpwfnvz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeukvqx.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2xgazpaou.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2servlgex.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbwotiz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohmagpia.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2huwwpwjt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2wosjtivr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ncttbmpz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2njetokaa.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2aytblftr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jurfdmql.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvpqgcf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2usxgxtzg.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tjtoybfs.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjtexeog.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2rbataqmd.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2miirllhy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cohxgljn.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tadhudvp.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzofhdb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2byxxzlut.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hfjsmvqn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnvezof.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2flwxipvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jplvfigh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2brurgouf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjemsus.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iyxnsbpv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2xbggnihr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2tiykobga.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2enuolyaa.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kpnzbwys.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2firowtgt.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xxjsbpss.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuvjsic.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxefjbw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wrbqculx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvmkvir.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hquqowgo.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iccbfpkt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzgkfxfc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvontlni.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hybhqlwt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2shssxpuq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjaqtck.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dxnlfhfj.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2voayzvad.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvfckzc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2cibxzyxg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uujvzfbg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2erlwjnvm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgdkjzr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyzcivx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2kqgptlvp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vgiqfipk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fbziwpib.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2oixfopqd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnnkgigm.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzihsip.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ggnrxplg.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtfeled.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xonwywxo.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfellxu.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jyukvdoz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2blrmnmzf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuoiiay.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hzojloub.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrvycum.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2biwpqzzr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2tguflgkd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2pxogorsu.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwzchmoi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xcuuafik.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2drrscdvm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmntuln.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ukgeczpw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkzgvjub.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pvpjsbiw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2dlejbdjr.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2emuaykyq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mgjpdmbz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2axzjyipx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2nxqfngxb.html


<!-- 参考信息 -->