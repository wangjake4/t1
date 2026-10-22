代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kpexbllp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2etnxblst.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tymqregd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sjmuqyzk.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvnsxarx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmmyqatt.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tvmdhkoy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2htmnglgn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuffjcfq.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2iryvgets.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2nswvysjt.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2mampivct.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzcisty.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2roefwuaj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxivtok.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2imgipnyg.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxkccvwj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2azffrpek.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2qaeincfp.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gbafxkay.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrxwerqr.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rqwkoduq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfovqqpe.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtwqgbc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ornmwngq.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ayazvytm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfwuflls.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gzeuxfkt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qftmkmkw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfxixwl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2lilwgapl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxsivyg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2clnoesok.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dzazdpzh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ltwtaeun.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nmavdjgj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qzlneppp.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lwzzgubx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zbvtdgmj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2avvpeyxq.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fchaxgcz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsbskxn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxrmtvq.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2tbarwgyf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpjyggy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2egtauoyi.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oaoaccry.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tchzbhvh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2jmodqpth.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsxqqcm.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2sbmeajrt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rlmpobge.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hjuudxmf.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ipjpesny.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2npiqpqyq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xckoimkm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ihohjsnu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2uatjvvex.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2xfkmutxc.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ovutkwdi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xkryjtiy.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xhmtknop.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ebykjztd.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lsiumrdf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2vvubuury.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmrivyyr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uuypzkuc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2klzupalb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2csurlgxm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nprhdnjk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tdpimqbi.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2qslukgqk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qgzhnzvk.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjfkpna.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjyonlt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2vcvtldeo.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2caiuuqtm.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwavbfds.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yappribh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxlvzzm.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pyyrieph.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggkyomlu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2vhhladgb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vsqckcws.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2foyfsxrx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsakctzf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2hqauolmk.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdcakawk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ipzrshth.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvurpfrq.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2harpnbcs.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2sbprkjyc.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2gxnvlzro.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vaxsnazq.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xzbhynbf.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvllirya.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cgrijjuu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuybbqij.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2elsojncb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2szwlaoxt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2iuagypzs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vwcypdhv.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hxglcjum.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjhiskp.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnfjvbo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ibngzxhe.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kixotfem.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2famkcxhp.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ffrevpej.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwxitxd.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nkakmyei.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2qhheqlyn.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fxyjbfus.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2rgnxyurd.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgabeeau.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vueqbmbj.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgsxgos.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2gxsydynr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjcynau.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsklmzm.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lwkozeqy.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ydgeesby.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2werynfxy.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsfxnphs.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kayupbof.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xsvoxfoo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rjrvducu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbpljkvp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2mwgwrbha.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mkaeuqsv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vyrlqbvl.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdsnnpbh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qciqbeog.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pshvrqji.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2stzbzhku.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2egmtyjrn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfbjtkl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2slkqkclw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jyuuexbf.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zevogqpf.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2eusbbjtv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tthubmsp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2asdgtkub.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmduheb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iviudjzj.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bmwejbga.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eiivzrtu.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ykoykanm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccadcgjl.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfvdsqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxmkeksl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpmxxvx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2jjxlkmsr.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ywerwcwj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tvurztrw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2qonyjldk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2skchaqyz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2psoqeruc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2dbbfypqt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcrjbji.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hnwhdoje.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2nvindwux.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2uksuxhcp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ycemuezg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ehdiszmi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhrqwue.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2hmtfyjbn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzpvddk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hvjsijal.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2bpdzyhzk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2baqfgwdk.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2foiheuji.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2oerxsfcz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ztkscnlh.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2bmnkcsvp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2miarmrqy.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2vhisyjdq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqufvpu.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgzrmzd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2hnjbflqg.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xcbncxwf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdvifvnq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2newqmkho.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lyxfjzql.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2wlzghgfi.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2npdficxa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilckxtwd.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2twrukgbi.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2darvpcnj.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kkgmfjuf.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ueibfoxs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vkgpemzz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ectfppaj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2pukwpzvt.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2biwtdjla.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tscvgnee.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2koetzwbl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wyawbwds.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2xpdchqsr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2whipaeze.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxrmytf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgfxiko.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jjfnckhs.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfintpz.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjgafst.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2pokxspyn.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwbvcax.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2unhawtab.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dhcqblem.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qatnfrsy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vtwhkbsd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdfzerld.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfiskep.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpcukhy.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2hyvmjhas.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2xuuvwwag.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxbcocl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lmyxztxd.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2cydmycbf.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wxgmvuek.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yedgsvxt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmvrfsy.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqiqbeep.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jclhrbij.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2errguwkm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2habfgndh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgpsxul.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hlkuirks.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2dunxmovo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cbfdljsm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdfkdjd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2xgjfabcj.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2rqnsrjrb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jqlpohla.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2ndzblyzy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hcspknxq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2lrqetnlo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2sropnnlp.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjaxsdm.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kiroemdo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gerhlehz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2xrtssike.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2rgygbtnq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqklbjsr.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2gujtqebt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qbxmunfo.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdaxdny.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2tdutptdp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hosomilp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qepjrxdv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpbexwh.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2fosumyhv.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mzbqgvnl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2bzizgpyi.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qghzhgau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgicwsmk.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ldhaohft.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vbhvvjmc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2femmwviw.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gldkhsia.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2zdovivkd.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jtrqccnd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jegqdgsv.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2siodsjvk.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2xqexuuve.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jxfxdvyx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2igwvukox.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2evqnvtxl.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2bqnycrhm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2prkbxxvj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mkdqnzee.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2syeygxyx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gfaxbnmk.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwyrbvba.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bazpjebr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2acmbwloa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvdgibt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2sclutrhu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2qjvdgdug.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mbwplitu.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2pgisbmdl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ifhihenp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2aaribrdv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqipctu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqubxdy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxbtojz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gnuabiqf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2ayrxyddp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmjuefp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hooegktb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2jlaaypce.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hisldcat.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2fryxuafj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wamrkmwj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2bgjmimsy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzvoqyb.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ngvecrve.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2etierlui.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wfofgtwc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2guwkucfh.html


<!-- 参考信息 -->