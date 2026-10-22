代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qmsmddoh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2zheyjzma.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2brfapbsb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2psdlbaxp.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kczqtksr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvkdxtwl.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwezznu.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2ultcnkay.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2ckknkkrj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ylabusio.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2drwkmwmg.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkkmvefj.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2znsjwgzh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xnmhgvkf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vggvpavt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2okbzulmv.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2teewciuy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgdsbjew.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aedzgnrr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnovjzq.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2slfbgfbz.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnfhjemm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fyuxmfuh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2twixxqck.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2qniapzdc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2mqnivori.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxotzdg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2phamyluh.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfeztox.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vxvxgjmz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2uhxkkddg.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdgsxqs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2oodforqx.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2sdqqmqpq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2bwdluuzj.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dmqmpemn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvjrkth.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rsehtybx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkcifova.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2qealnlba.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpmeuhg.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2fyrjqblp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qegnhnhf.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrszmpw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2rmsaejay.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2csmgznlw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ukqeuucs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2crjikigp.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2avkyrzvh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2czpxkhpe.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2iqdhmnyl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2isxogghd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uhtwysus.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jywiohta.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2zvkutqox.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2axhfotmp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xoakydmw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wbfijata.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vcacjtbr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gfgvzcqr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2dfgipmki.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2shhhyatx.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xekyvkpu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxmpksi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvafqko.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2zhqjqxfz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iimherkb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhrzmshi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2gherbqoj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdbowbzc.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2iywgwnus.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsjzfed.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2ogynsivb.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlutleqr.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ivmpohyo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2atxrmenx.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxqyhoi.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2amfxycqc.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vbjnswhk.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2btgcsccq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fstzereh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fuchybbk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vezpqrao.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2hpmikdzj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qxdmgkbm.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrvmkrdr.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwsggffl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2szlrjenk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxpzuqw.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cigrljuy.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2emiivhbr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sngmqurf.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nzbekwvw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2yllneutq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rzgsqxeb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tazdrnac.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2eshaunon.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnksqcgl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dmsauvgb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2adebkmli.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2yyajsrda.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vagasaxz.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kypzdytx.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2diyktwtj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2igpovizu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2yyrsxwgg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2zbadrjfn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hddmspfy.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdadwfo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mnuwgpzi.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hfsmcbgx.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2qrqujdkb.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2infqndor.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2zrejxoej.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nxpgqknc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeennwz.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wftnfqbd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2siptmzjf.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mdiwclvu.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zetdhamt.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2llchblar.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wrawokes.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2aiysugad.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2yrumywky.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wuhtbtft.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vokxaviy.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfyafnb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xuwihzem.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2phyorkop.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhwbiaz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2aedhpjhs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qkfbjnuc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2adjlbkmp.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2uqcyyqqf.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yexovfgv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbusgibv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sjkrwapq.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsekrnt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zbctzzni.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iaeupusc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kfssdqri.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugqgqlka.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kchkydwu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibdppika.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2haaacigf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2twsttylx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nwmjywps.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnhaopkk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nswqxfci.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pazxtvdo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mctomhkx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2pjcjobwt.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hccqfleu.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpczflp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdfuhiyz.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qvclqwed.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkbttgjh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xapybnap.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2asccvjfn.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2avxtwdek.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2xaoxjmwn.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qdrfubtg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2toccszjn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2uevwavcl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2afvqcmvn.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjywhqn.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrwzxyxx.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2svsnrscs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbiepdz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eseigong.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpkwfii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vegrupqb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2aknnwltm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hoiuzxmz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2tnvqaztf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eowpvwjb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vgftujlb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dvegzpjr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ulgcgrwy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2smrcnomm.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bflyjxqe.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2hfysjkeg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2arxyjciy.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rfdhvgby.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgsdwcam.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pgmesscw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2snngrxrh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfinnue.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ourcujot.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kbdhcddg.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tddwcqzp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wtocatox.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2adebgkfz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2igdwahkd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zutzemfi.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kucktsmr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ryrgchnj.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbhdxuix.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cubwiqat.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlcbixa.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ycpexkal.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxnztdk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxuhfpc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2mjiipfmg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2szotldru.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfpojfk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mkptyiuu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tcqkzitc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2asgtwrsm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2txsgebsg.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2bwwzymib.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqtvxsrs.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qsemmxbo.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsxuxng.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2sitbrqhi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jbiwilqc.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rsfzggjb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2nrktylkq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ygpprbef.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2drzgxdoz.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2csgrhjcy.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxhkursn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmyxbjb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ryyjowrt.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lhdiwnsb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mnjbnbvd.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jskmdrxe.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2swryvkoj.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jbfqleyk.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2iypwmjhy.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvqrtpj.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoblextl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2shpumsos.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2leyduxvt.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2mayelsjh.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cqqrrwck.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ajaiqmql.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2uwmrwfzp.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2bjlyvaxu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2yejtcnhm.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2skdoqmcp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhkucnl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zjnegipj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqmayic.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2pospepss.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zmdnklyr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyvrqyn.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nuqfwybi.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kqkbgqkn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2alhxtwnb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tndrljvl.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2knoxjroz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcfkfux.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2luyyddiu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxhpoqi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2lbsruhto.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmvyvdj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgoeufs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zngicprg.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qbrunekl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zxclnzca.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwifyro.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pbxelcao.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sylmeeym.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uenzjsch.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2ddptauqt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ormoijad.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hoobpsrr.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2kitwhjfm.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qerxhcau.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2mufjfotb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vcnybrau.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqrbwqk.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmhxswxv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pcwgzpwe.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2piiwkvln.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2jnvchwha.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2srdrgida.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cnqxugeq.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ndoyvrpp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2elvpgapi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lkgxajuk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2zsyyrxir.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cublrhtt.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mdcgshjw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycheabhr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2dxwcgxyp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zchlcusd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2excjzcgn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrumtuf.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nxhtkeww.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbeiexbt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ohdoccng.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2flfccygb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ojnawyjg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fhnqhhyi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2akgqetgd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2yhosxbtg.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fnszabgt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2avvcuaxg.html


<!-- 参考信息 -->