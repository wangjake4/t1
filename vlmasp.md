代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dstvshvu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeyoczp.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2syfraotd.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tqytmwdo.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2yrxbmuuh.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2lhfmojrc.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqotuci.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbkdvdx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqksain.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnmgjym.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lvyrqdjw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbsrpjgr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ranavhiv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unzjhluo.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gsujouqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2enxdkgkb.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmdiatvf.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecyvqcyi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxqucnv.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxpzyvdu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2tytdxmca.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sujmtowd.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qjiqzdft.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvpmrdo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgoqrhcy.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2qdciscss.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrtrsgq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2auzkwweu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpeackc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2waxhltvl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrmllet.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lsanbjin.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzrgbehp.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2euwnloum.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxkwfkr.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjhutpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdwwcee.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhznzgn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtpnbca.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2fqdbzknp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2czpjjaus.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jhfyuugf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2iznkifcd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tphllcsd.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jdxvqjxq.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrmfhvf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jygqwujy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2rrzmysfu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjlezcg.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrbzmgcg.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2tktiubct.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2upxagyen.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ofydnooa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyyfpsm.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2zfkkkcdg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gapzzusg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cymyfmqn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zrqeqbaw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2nrttxxew.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ivpaosnr.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2drjvhtsn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fxcvifrh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ppsnxhdx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eqzvuvbm.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2yqoekvea.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iwnryhcb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nudljfuz.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtxvzxch.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gijuytys.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qpikmrki.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fccbpuzs.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ekasopdv.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2dwmutvdn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2jouwqjzf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2liaehrzc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2somvhvda.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwbvfsw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2cdhtpjqr.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qycnbivq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqxglujc.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2crvpniyx.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxywflmg.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2jagfsdgx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2mwbqytuz.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alhbmcnb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gjdnwfyg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jowzlzui.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mldlebbq.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2luqzckoc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pcbuugrl.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2elthihal.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2irepapvl.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2udtijkcf.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2aogfwpie.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2psyziycj.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhszflre.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2uomorfym.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkqwtku.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2surzejvk.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwvjmcm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hlzomhak.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuobaqx.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqkjmzj.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2truupyxm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oyjtvzek.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ijezlliv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xabdynsb.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2ddhzuesf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sggvolti.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rkkvxpgj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2nynafxub.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkvwvxn.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2eeiueuqy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vaevvrat.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2joazcefj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ldirbksg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfpagba.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pyareukw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2skgocjwp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2oczevypj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wlchbzue.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwdjrbs.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2hekttdok.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbumawe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ubdkxudk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvrjxtmc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2milrqubj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2biyqyonr.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2iaroftpm.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2euhyblmc.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2fcsrspvk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tcggsycx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrpzppn.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2msthxbos.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2wckwaryf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwwlzojn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2saeswmcu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrwbrtfv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nieazunh.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2eidapinn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xjetxbzd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsrurdl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uknwulgl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2yypozvrh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxehxgfx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgrgnec.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxlgikki.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgaxndl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ybxbdqas.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2boacvhya.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2fnqbxtbi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mnglscqe.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhqndso.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2drnqqtfs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xexamjko.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2qugrxlqt.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uksjlrrh.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rwdlvosp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2smdnueze.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mfskrmqj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2ldouyaps.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cmojookq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2qufzwfjt.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2swvgszaa.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjldvmy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2unmsguas.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2hetjimgr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tnrptavu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xshtujdi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhkozlk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2oxgtwmmk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2imdfjmah.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2crdoyhhy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gcmbndrj.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2edysavre.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdvxldo.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpepxey.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhcesky.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yptekbhp.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tinkzqfm.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkofawm.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2risgijgr.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcmscvil.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vkkjvksm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2zfhbnowi.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjssxeri.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ongubeyw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2apmxstyf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lqujmqml.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjzkvfp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuoewmf.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2euxzffss.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2vyufitog.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2eircdwfa.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2rmqbkojf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtkkalmj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqhzgpc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqqnobxg.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nklamhsx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2avcdjvsz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nprhrfqh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2asrxlrsn.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2smbqvjkm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2efygfdje.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2hmwwxjnw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2xswobjha.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2wohtegjk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnbwkyj.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ykkrnynv.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2elgacnzs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2gnlucbfa.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpboklt.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yrororct.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2fuoazexh.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fsjimthj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ameomqwk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2bxvahhbu.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uucfyntk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2frbhpzsj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2njfgfijy.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaspurj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2djuebfye.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2gzkdrayb.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuoblha.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ykelfqzg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ronaseff.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bxhzlxsq.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2uocrpcvi.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2pexbywtg.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlyoetj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jjezmrco.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqmuitu.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2yvbxfaqe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2yclrfdmx.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2hycozlnd.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppdlepnj.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqchuiad.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2izovyxit.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ivcajhro.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2wadgaazy.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2zuladcjp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2badkieoz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2whkuxsvg.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbvkusw.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pnqniyif.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjqsuyv.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbmwxzu.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtezuepo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2zubtkuzn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wmcvedqs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2poltuwjk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pazcpsvq.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kviuandz.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbswjbwm.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvalgro.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qoszmlxe.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2dudcveln.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssqswxuv.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hxqcwzng.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2zkgvfghp.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xoivqdpl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2winmsdgr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2prjluymv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jcegzmwf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2llpfttrg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvggdse.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2cuwipila.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbknlby.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qnyebazx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tjeyyatx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mocxpcxc.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2twcxgpub.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gslqrmai.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2faxyhtin.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2qexjtbko.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2rlopbdfi.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dggyundk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2awzggixk.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ohttbthl.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvzddbgr.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uqipkzmw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cylrhufm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2sleudmwg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2cczgedgj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qukxtswp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vfimqfjz.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2fhzdhwlf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sloddwym.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uyahidgy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2kfalyaqm.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2sizyrrvk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2joqwuypt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiryjhf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvcgjwy.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2nofmpxka.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2yifggsfh.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2hrcsgbpf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhiohdy.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mtnxtldr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2vesppnnj.html


<!-- 参考信息 -->