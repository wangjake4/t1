代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqwkouu.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2iphaaigh.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2wucncxoz.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fubqdjny.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2vjojemqs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bxugltrf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2psjvlbln.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdsaltzn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rathtshl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuwerebb.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2btzyjmhs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2mturlctd.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lcnkedyk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ikupvrqv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qaazhthj.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bttiohkj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrgiydx.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tgsrkoks.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvhdaey.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrigxar.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xhcewipx.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzpncxf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oayercpx.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uvdtqedv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhmygaa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2huuizzwq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfvtlcpu.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dthzmypx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xdbjksvy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgihownd.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2puuwwsrt.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cecznant.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ezzluyom.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2uzyayptv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xekadzli.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2cyugzhqb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ukmzzvlv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqecaggx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2fcmqtryc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qgutgaav.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpqvgbq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kktvwwiu.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrkmjvde.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tmhaytuk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2vihqwjwr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgyhijy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmrvear.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2djytazln.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jyhwfygq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vdykjuur.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ayttfeij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2bojqjtsb.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnpbkbk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2mmtoxlok.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyydefd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2upzcthpp.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zmsuztll.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gkbucnrf.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlihwbf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2idyjjpih.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2oqqskelx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yckchzex.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2gnmwyoop.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dzhvmvtg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wipftgqt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2paveexka.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlbylvp.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2slkpixki.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxmguzb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjvedkv.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wgwbyspf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yyndtsff.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmbaaev.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkfggya.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eykfjpcz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmrqvrs.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ctilpoah.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnzlfrfy.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gongabbh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xvtowmpk.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dfmtthuc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwvpoqa.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nhlnbsei.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fkdqghyj.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2useyhblb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvtfaml.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2qkhblgtu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ryzsmgzi.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2svdvoass.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zafrgxnu.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2eontjbxs.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2oalvxuyg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jeloozfx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xvnugqph.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bvtltjmd.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2zesvmwic.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfgndgh.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2evpmaplg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2wmxenpuk.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaneljks.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wafhggqn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vtibjlye.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyludlc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbgwgly.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2itbbprys.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2joazwvtr.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2squeqlkh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dhyydsov.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2yqqmtuno.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2drtvpvww.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cwndswkn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2cyesreuo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ecefluox.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ztticjox.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2thngwjvv.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2slupfoyk.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qfedzood.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zqjbvkgt.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2faprgegu.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2lxqdmfnb.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wibdudab.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2asruwqcy.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tomfiqkk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2myajtwrr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvyrbcd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkyellc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fggisndx.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyykevtb.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2goloszwn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ofjtmiyy.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2urlsbyym.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuodiejv.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2uiocmbwk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mossvpwf.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fvousbua.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2mrbcrwjf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zzgebgmv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udhnubcv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bdoukwka.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2msndnsdq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jihguygf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqobzhl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnswxbve.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xstctswj.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vewgljkl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2piezcdky.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivaxyakt.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2eerrrijy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvfnzqv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqdqhoj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jadsjvnx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwjishj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfentars.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2dahikiuj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2qckjvfhl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dvzlmxty.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zinqjxdf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2enjdfbih.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gezvacid.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2hfkuaoja.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2herqcsue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjyxukgq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2odslrcia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phwbyprr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2egqhoiof.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hrreehri.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2eyoqhjwv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tzznxart.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2yaalvele.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2lndjnmjc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2istcnkde.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdgxqhb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiadnln.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2nfeaoshn.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dqjupyid.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2jtillusi.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2yyctrpsu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tofrxtsp.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2onqmhpph.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ogczsehx.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2npbtcleo.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyqaytsp.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeeeilu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zlacoxtt.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaoduhx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhmzyta.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2thqekmrx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jeetnpob.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jiimrttl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwoebbu.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdhrmqj.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsfsarb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2twawpepz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2gkngyqcv.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uxdwlttc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2afdgpguu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2izgancwp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2cshsoppk.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwtyvos.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ttpixalc.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2lbkvvrtt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mznmhtqc.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ypbmkicv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2frwqejjc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgmukfy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hogvixqr.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2mnayknsu.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bwmtlhbt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2feklwaqw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2slsqirla.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mfmlmffq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hcpcnkqm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dzvnezew.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vmoecegt.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjdtojp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2oowyilqd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2hfmynpqg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2zgyarizi.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqbpsfg.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2wyzrswwd.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wjgrcysx.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2kepyqkmk.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2twlautya.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2cmobevna.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ixzpbacw.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mddphjgw.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwmjjci.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wlqhahah.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2cxfgmmey.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zlmxzzlw.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgbsqrn.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hdocvruz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2npxftvml.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnyofni.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qcatczvn.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxduzesy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ghohvelj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2agfssyup.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2isgnsgml.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzxxqfn.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ieemuaku.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2otkuwvmf.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2gpdhijks.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvagezgl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2acxcjpez.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpdftme.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dhnnvjgz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwompdsp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kavqafrf.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdqsuiu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqeviru.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqynfjl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ttqfrvmy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2apsnqyya.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2umcogmsq.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mttcumrv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2heqheygg.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bptiuerh.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kvqucjvv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeyzjtfb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2qxpmcego.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2cubpzfuw.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkjdggq.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xqgjufiq.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qbdttmxe.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ghifegis.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nlzhkppl.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpapejqf.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcvmylw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2lmqjapwx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2zntsangi.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzzyicp.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2nyulpqgb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2xrmhehhz.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rawegveh.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmyvcie.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wgvrqwbo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rcgmiejs.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwjlidh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvyplgyg.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gukjbnyl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmbnkrwk.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2esxstvly.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2hlolkllt.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pctkupzy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaqfcrf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2ymldgpik.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2uguvyhth.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2oernahco.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2plnlpnjj.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uvsqawee.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2svppbfsu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2filyumrd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bxorbvhv.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2gdphghss.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uslopfvp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkicoqf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2nlbtltck.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlosuws.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zikswrof.html


<!-- 参考信息 -->