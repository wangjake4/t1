代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vvslkhoz.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2pyflxnip.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjvovvo.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyneiukh.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xibaxztd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rskkqaeg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xkylkmuo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnkqrec.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ajolypqx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbariplk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qoolizgk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2egcintpn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2murviwbv.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbytatv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvtgptnq.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwcdeai.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqicapu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2uonydfjr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wnekpqsz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2juavlrdk.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nabmeqmg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2wkvupwek.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2gznbfdbt.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dzftdaji.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2iilpfuui.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2edsrozqc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgualvz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqlstop.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tecnnroa.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nnaotpfo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfthezuh.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqvbcxj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytxxupxy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2kjeczagv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2rvnfhgqq.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2etauhmsb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsmlqvw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgndiwa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2cqudyefl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkcvxck.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sorhmovq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qzdlzqtj.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zctdhkme.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2irkddibe.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2izjicsnq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpisdpk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2efkiirjv.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2prblbibr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2rifmaqme.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zyxgedes.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2makipcxr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2maskudai.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vlbdtlss.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgkcbrw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2chveqard.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ohkyvimk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvjpyew.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2dbemqjap.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2judwflfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jgntxklq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxmlqro.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qlxmeubd.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2rasrihqh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wqsrnfbr.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jfjshrrg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeijqxp.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcwfqlb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvqyodd.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2lzhxttoh.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cievdrsd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fmmsuutf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwrifli.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2arwmquaj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vfgfbkcc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2nrokokfi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2navyrazh.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zkcsueel.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rygejihm.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bzzbaytp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2eetmzrvh.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uuxroicl.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oecgvvpn.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rmvgrvyg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hpssvmsu.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnxlqrw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpjwekw.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwrucrk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykzancur.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ysanzcai.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2lkoflaic.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2dyvhchaa.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2lryglrzb.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2faazwpvi.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyluwmzr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qaioxemu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrtcqhr.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2qxujoswx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xeiueytv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2irqmpgba.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvnhfht.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgeirnj.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gwllhcud.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nphbuepn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gadkmmtn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2mdhytspx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2aoxgqmit.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2sdujkdjf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2indzhpgr.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2uccmjpod.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bdhwshey.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qmymatnk.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fkqkocgo.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lwlwteeg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfsxears.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ssygsyaj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gakvvsqo.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nrdavkrh.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2vftgyoaq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2joppehsq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2fnowufhq.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uzajzkny.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2wvmwdjkz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dhhydjzd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pmajoqmk.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bgrodjrg.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2wijthgvo.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnrhjmy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkoklef.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cpmmafnl.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sxtbtpaj.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ikigrwom.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oainoynt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2nzxspybo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzjvqyjo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2csnvgomc.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmufiae.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fqpaeotw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxbihoz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kycdiuuj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bqzpvpyn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwwmlknq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2orxdounp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mqndolvb.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wpegdpoe.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfergbso.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2acwiywgl.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ncerwdtn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2makqebpg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2dbsdxblv.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pxrbbols.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixxcbavq.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qriecefv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhkgatuk.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vstxbtjs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2zxktboja.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gyfwpnle.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dmvkprqy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2csixbbrf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwbupeda.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzaywsu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2stwbxlpl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xyvbhows.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2mulukets.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfbvjtp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dayilayl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfymzvd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbpqvou.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2acjzfjat.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lkasqskm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2xgsniidg.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mhkqzdqc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2unbxrbrh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zwkhxahf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixwhexzd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yhgnsevl.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nyqpsvxe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbswwyk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2rinlgelf.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2nwyixlep.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2guvhyvnr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2szdhgoiy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwrwbcds.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mpvtbdvh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ketjfheu.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2innlwjcy.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxvayjbu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2comcxclz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2bifhelpv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2yupkston.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkpoivlw.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2pghubppl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2fisesguu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xedznnvq.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2oheffriy.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uyyjvvcc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwlwzox.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ziyzwnxf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeruiqg.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rvmhxpza.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fnjdiefy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2dbcaqibl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aedyokee.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2upsijugp.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2oujfakrj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2rkmliuvi.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2rzcmdtek.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zoezzdei.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdajvocg.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bonqkqez.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2mwumuyig.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cdmrzhcw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2omazbowd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2lkmqbfto.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqsmdgg.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2mgcdskfh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcvmlgpq.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfjwhvy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dkqzkwah.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2iozotmmo.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bybkrpxw.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2wostwrmu.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvefrng.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2txxlqddc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpcpiewd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbxcpys.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2mysozips.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsirvke.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2tinnowis.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpzhcot.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2zxtckxzj.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2exwheigj.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2tofcbwpt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2isklxwww.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtsrkjkn.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2oftjjhqi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssubuiqy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2orzuadcu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2dazbkhks.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwzzmzp.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2nfyhtkzo.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gdpmkijn.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2zkejvyec.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2isjafdti.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2neagcujn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2owffydpq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2aevxmfqu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2odctjmui.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mecwwjub.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gfizfnsl.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgcbhusg.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vndkjnsr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cglcmvkf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xqnssptu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cesuooxg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2doopwxbs.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2lkntphpm.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zhlvkmvm.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2klbxxiwr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wlwbavde.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkfeepl.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2apeevrmr.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkcvmsu.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vyltgwtb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzvdqub.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2itsghgpg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2ladmcyte.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dobadblt.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2yjrqvgco.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2trpjzmdj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2dujdfztn.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxjcvoz.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rluiykqo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wackqrhi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ksckdmzd.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hhsktrqx.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2drudcigm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tobrhden.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ewzefpuz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2gawliite.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cunjbrcc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jjffgdkz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uipaagpp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfigkvd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kqpyssbk.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2vofxjbnt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2pchnwnvy.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rbjpcsen.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wkkkdcit.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2egamrghg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2rcxbkdeq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pasxdabr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2csztwstn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2gpuknocy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zardknkm.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkhakbp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2uxipcosv.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2groxmoav.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2iofwixqy.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2qdizytlx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2zzbmtuig.html


<!-- 参考信息 -->