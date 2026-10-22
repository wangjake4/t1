代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2qvksodzj.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2afzvijov.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxwcrok.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtphyaqd.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2zeordfqv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2gfyqcrcy.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2muvfanja.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kunyunua.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kgthxktr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2etzkkikp.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fzayzrxd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ergpfiyp.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2taqxurpa.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqsmmzc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2urbkwhep.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rxphefzn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rjgyxxsg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2oulpicmi.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2uzftvamy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2giipvuuf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hxmpsxbc.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqkatyz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2txjjsfgr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dsqjsssw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrgpoov.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ttorczvk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugaidegz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvtgrpi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mizjgczg.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wlxhmanx.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2uewuwagp.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2lyeijvfd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tengqsxu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2rbouvpfa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uvoxcrwe.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bezhbaep.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gubabftd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dyasiikn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2weyvwdkp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iwdzswbo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wbxmslkb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lfotrvcj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2irtxyoor.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2whavqpxn.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkugnrs.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfpkcrrq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tgyltgkx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2njxsljzp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2buvvxryu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2glxgnrzu.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2qadiuxlc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2delhslfn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2upznyjun.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2kkewaysn.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2puskypbk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2oxltympg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yzvvlxrl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2crbzeauj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ympkuexy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lknotcdu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2tpaxhxdv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjiibhs.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2havefhqd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rffxrrhc.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fizictdn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuysviqh.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2frcregud.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlzlgpp.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qyijzwrq.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbdyksp.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjetezc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kooajxlu.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pcfhexke.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mneuuwii.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbielnt.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfxlxpf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ohtssxdq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ibrnmvls.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jbnelyip.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgfjvyv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyuwyty.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmmczrj.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zrsuugwq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wahbkejb.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqhmwopb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2mvxloefs.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jxqsunpk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2raekxuer.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ceieekpg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsvusvx.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2bgkcpsbi.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2scjcwnnn.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2lxffqgmy.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zefqbkao.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlfafko.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvoeaim.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ngtoudcx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2eflelptr.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rmmbihdv.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2opiodxwr.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqpndih.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuvozpc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2evfsfnbv.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yejefzcm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqtvzlje.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rnnufbiw.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2cwxyyrsy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2jlgbpuqf.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2trcvccdq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eyachxci.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ggezkpnn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2iqfhjcbe.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ygxlqgxv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrnpntfm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2frmgtghv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2lufkojwq.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bersttar.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kwhejthp.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2krtaugwy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vdewghmu.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sohjuzmq.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2asdlxtwa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zixccbmn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2jkniizrs.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nabnsdhd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrmbjntx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2yfrkjgjc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyxfnev.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dekuyuue.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvidkrp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nfznefwo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrhkjiww.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2wwiuopou.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsetbkrp.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2njkjombb.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbffdhm.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwqzryv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tspzcdjx.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmckarc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2zepckzch.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrrjdik.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mhoptsba.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsnsvyx.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nvzifmwe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2umgwlrty.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2einvgorr.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbvzfan.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pjyimrob.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ozldvrxg.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nutempnz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2otqseapw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqqodhs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gkujsgjg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2krpyuyhp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dljazdmr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2peevinqp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ezdqasjr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2koplsdbz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzqqoxk.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ywspkygu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtdauwo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twiuiexp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2cbamghlt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nqijkafc.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jufkxtox.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwusbft.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ehcjbjrm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lztiyxta.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2qlwanolh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lbcefext.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2fotjjnqp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2cxumllas.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kvurlppf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2kliiqtvt.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rczmpece.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gjbwhhkn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2iqtggomx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2jntzepih.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wahacuga.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dyjlwbmh.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wamjfyhl.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tijtyxvd.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2awvfnkqa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ohridyzv.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvyhdfu.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2juhopyoc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gomnwuyt.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2flgjsupg.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2poztvvkh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2gsogjxol.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mcrzpxbs.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2aekhykyz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xvsybmol.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhixqpeo.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xrfkldft.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lpypjxoj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbgcxeb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2keltmjye.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ftbevjxx.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hszjajpg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2xahjoitr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nncniuzy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2mwcarkds.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzgvqcqt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2qznvprih.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxroxrg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2fzlfbldv.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gdshkpfo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2raelaujh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2gbnqvurj.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cvgesrng.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tzulucib.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2xksewowi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmatnsm.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2tvekvvee.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2alzlmwwz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyvrxbt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2coefbyiu.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2zklbrtux.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2agzhigav.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrxeunn.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kvgxgykh.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sgtbjfrn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wptszdkl.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyxcipl.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2juyltchj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ryysqsux.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2oijjyead.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cltvcwwn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zbdemejo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2lrgmvyql.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2deoqlrvo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbvuqhjm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyeliuer.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2awttquej.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2jowfgrrf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rdotxcpw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2fzivgvcr.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pouudeus.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mhrvyqgh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sobvqhgo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ljbhioau.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hbqnlnob.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cdigsnax.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2waptvbkp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mqzrvlnv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2biyffgpo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqypdfdj.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ujwcluxn.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgplzkl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzrhqan.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzwgszzm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ajdcrwjj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rozksqlx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2frucjmxr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2yiikkvvx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfxbsem.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkeaflp.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2fzngmdlj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2graqmgws.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lfudttnr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2myexgclx.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2itctfcgn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2ltrbrucu.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2etxrwlro.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnnhinlb.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fhjcqdip.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfkfcnt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cuzbrsgb.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2gbayddvb.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2yfklghgm.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjuwjpy.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2covvgkey.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2rzmtaykv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qytnqyvl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ymjujomy.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2taifupqz.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2mwyfvthx.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2siohoksd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mafnsuxx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2yxgdshdh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hqtupgjh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2stlrdize.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2beroppaw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2cubouwbg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2imdnwgba.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2kueqeomj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2aynmiksc.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2ezikgnaj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwabcuhi.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fumvgzkg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ngavuwyh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2pqvjcozv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sokrarnx.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qiptinsy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2getjvkou.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2sevkdkps.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2izabnodz.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2zilchrbt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2acxmobzn.html


<!-- 参考信息 -->