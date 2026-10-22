代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vqniwfgd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqxobmj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrjjoee.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2oflrlnxa.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mdyziqxd.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2jqevkwux.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2bvswcyxw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsngqne.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xmskqyjz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2opsfnofa.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2prnndafx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2snombtmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fmnqiwkt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjiglazp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzsnldu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2bonyxxpp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rmayeufb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qwpvkgig.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gwnhvuaz.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2qdgcfzpj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ordqyvqs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vhecjdty.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvgwsie.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2iwrhljdv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqnrgnaq.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2osbgtipi.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfthuiex.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vcccdocy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2othnmtzq.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhgkhwz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2soqgjfzn.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2hmaajvsq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxmakml.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpgietc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugtvxhac.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2fjywtyly.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kpcrhirg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdpddrv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2msfcjceb.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2yfhborca.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fzncedus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2plnwxhix.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2gzuwnyuo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hykgajfq.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ezsenkrw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jmjfcakb.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2khpvlgxe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2clcyiqty.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzhikfa.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2noinhmoj.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnhiqfs.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2yatizmcd.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tewtcezc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wynwnaha.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lxflurgh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnuqdphz.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kjwjrqlh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2umripgxy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ijisocfd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bzwblrya.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cypbfwwv.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cykxqdpd.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2janjkwsz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2otzzndqn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2assfiohy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2umigsadp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2qojvthct.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzttjsaj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qahyombh.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wlicuylg.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pnjjlitx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2znvwsbil.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiwkyvk.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2kgxbhepi.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gcamekhn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xpffjqwl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxchwah.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hzlmewse.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqubzwnf.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqrmnxo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtiympx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2espawxcc.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ahxnvqjj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpsgcppw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dkctoxon.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldbfpqty.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkcwqjj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrfbifxw.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kwixhkuv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsyzpppo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2phxzqyng.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvofhfo.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2iaigsejp.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2oorqobhq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqnqedv.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzukuix.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2glwhrfye.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xfbzshht.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rtussbvv.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlrtyim.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nrjmsgan.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsjktmu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2omdutdfp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkvjods.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2veekhfxt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2itbaoich.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lgirvkdw.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2isfyslet.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsegdqo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2lvsiuyql.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hfeamfai.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dvykvwse.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yvisdlfx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwubbik.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qiwartaq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2taafkdep.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2etnphssa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nldxvgeh.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkkjrjoj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uxbjdbdc.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2sruhbesx.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgwejptw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkgrmwz.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2rlybqwgw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwboprk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfzsamku.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2crahynxi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hwfckfgf.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xiaexojj.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2xegxfmvi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2epkefduc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2icpfstvn.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eriazejc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ejdxcnhd.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wvzajwmg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmzysfjx.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zorwygew.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qoiqggwo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2snulwlci.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2avqhxpxz.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdqeezy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wndibkdx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hhvvsnmh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcgqwmiu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zyufaqjo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jfhlspbo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xbcgfxca.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2guulthdx.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfycvnnf.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gypgrfay.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2adyxgihq.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kgursfjr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsobqpcx.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2omtdgnov.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eskqmhny.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2auwixwje.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzuueqs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rpsopmrn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkaaxpf.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2qnzofmne.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2naprkgrn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2frmnjshm.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2budwfeai.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2haremdfc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsbecai.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgdgatw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gdagoorl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwsskgi.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lwxkbjag.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2mjdoiokr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2nvmqqisx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpdaidz.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2onpgvrea.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2svhvnrmn.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2evtmhbpv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2iheaddcv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2knynjfzz.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2jhsjlzqq.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2woxqapqj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dcsnktkk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2eltxqbnx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2refgebtv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wpwkcodc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jitppxai.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2judeaeti.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2fbgsdzqk.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nmwtvdcd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2bmivocaq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cdvgexhp.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdfvnckb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2upjdfzol.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zmpnhlzu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2krmkiobc.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2vajhapov.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2jdsvstco.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixmpexqo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2awmqmcvp.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2poconzcj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2tphzrrvi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hhakuerg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcszloq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpwmuuh.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2opgejbck.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hedwnbyn.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjvhxfx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ziipktlb.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jvaobrqx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjmcnhym.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2otfdktwd.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyaxpfc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2djccgtif.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2xomigjos.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaghmwzv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ftnpwuxy.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzzppjw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yowuspnr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmldovp.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjnxfya.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2citkufbe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vflakrtt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xxqaqdhs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2axjlfntg.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kukuihok.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2qbummxkk.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uruzhekp.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2nguuaqdw.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhdnqre.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaoeffx.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2przfmovy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mktudwkz.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2vzijupph.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ujoxghsg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwiusyr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuxlsnmr.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbarhnt.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2flhoyptv.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2jesjtvon.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjtrjcn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2guelskus.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrpkvgcw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2urdnmplu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2shfiyien.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ienpeuws.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kathwdzn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dqiycuha.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmbgixy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ypzaqyuh.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zczmqfuv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qydhhcig.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2bfjhtbhw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2izqrgemt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvuyelsj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zeyuxhvh.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjwzvokw.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yscbhicq.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cfautjxr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2njrxchcb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2chgcgmav.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbsmklq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2xpboyomx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wgaiekle.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hvefdaze.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2jfwyzbem.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fqvwfuyu.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ktcxklpn.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2answrlwq.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ybalfjmk.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2urvvdjuh.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2swhwywfh.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2emrhsqcd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyumuwd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2sahmsptw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2udlmibys.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2khzclqzj.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zqmzlktz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jxjysjjv.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2beoknazh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jfiagfvv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2sznuqyny.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2orghwnps.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhuemzl.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqeffpt.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2qxlmvbxo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2kotowouw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzlhprz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bblxtjxn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2axeytqbd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfwvbptb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2exnogsny.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kaycujuw.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2svwishyx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2hirrhtph.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2zgbbksng.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mtdsqrfz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfzkhdog.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2qizmejzt.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rhzipfwu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggixkhkc.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jksttjvm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwytmsmx.html


<!-- 参考信息 -->