代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lciqdmtl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2tavdomaa.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzlaabr.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgswkwv.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2xxptwmth.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwgctdiv.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2flojwyah.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmkfoff.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzissve.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvmbrho.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2tmvxznrd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2orbncdpa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2breqlnmg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2reoduyod.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ywhjfadt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjqgfus.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tmndipeb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rnshwivh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zhyedckc.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtfijhr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2vkfzebbs.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2aticbqvt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkkoydk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2cdjiuzep.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lijumybw.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2lkbhzqmy.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2szmwlpbj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vqylhlgm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnduhxg.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2vlrnfrzx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcskeoyc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2atfoehtk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhsewwf.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rxwuyseo.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2nivtnnvc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2swzosswp.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyepefqw.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrrybje.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iasrnazi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zxyskwwb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2wjpjhdvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uwatpbav.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2hspddxjf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2toplixoa.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdtrnehh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqyytwha.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qngvavgf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2nesxqadb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xxxohjyy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajqzilpw.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2wtniquqh.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2egfestby.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vsisnxle.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wkzwxpqp.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfpihcb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2odounwcj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyhamzg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qejwkwlq.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2tzamkcro.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2bmywoqoq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2oygwrynn.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2aeoynqtl.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rubigmpq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bhbnovup.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2adhldgkx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2kxgyivcp.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2delstber.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrfnnwy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2jquakqua.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwyakvri.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qocekgoi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfyynojq.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2upsxgmvx.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmuzkdh.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvkfghf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2knrbovfb.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xxnlljtn.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2acezsstb.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2holisynb.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2croppuum.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2itwhslil.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2knzqgjyw.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vwkvhivp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwfbdnpm.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rtfmznod.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2maormold.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqchxul.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2thbwevkz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fwmgtkbk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pdicqtps.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbwcgcv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihmrpvxk.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2japmktvo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqvgdk.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2afhtqxkn.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnatplo.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ovsoppna.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2avkbfwce.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2nuufaxbz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2pajxekgu.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2aaumvuzl.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2hisgqdcw.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgtxqnr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfiaeypc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pqxufjfv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbtjvjbc.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yamuwsct.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgprdzf.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2xbuewxcd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2nswxapoi.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xdeodeyi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2oqvetzxv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2phkkalom.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gnnlidrd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ztstuque.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hhponvwb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2owdyjmaw.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2dybzglnt.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjbbzuf.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gntnufhe.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhylegr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2fixwrpjf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2cziwuzfh.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2nesvjxqf.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mpycblbf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbdtqsd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2niyilymb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ffsrqako.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkxnrnx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2upyzoqyv.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kuldvkun.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbtenvpd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2uqtydmij.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbdepcr.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2uwueubgs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzqruirk.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbiyvpr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cuqjqkbg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zalzfnal.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2pqrfjckq.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2apawpgio.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yaemchyv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zvbvmezy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpzggit.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eusfjcha.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ovidqmam.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lrylnosy.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwqfcdu.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvrckyz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2emfrfhim.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfzhumi.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2fexsjgbm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfeaqwbt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnfjjyu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhkkbcx.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2duawbctx.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxjhint.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bczcrbch.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2opzmeqqo.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kujasqsq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2bkbdndhj.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lxpxqzyr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2itsiiexw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2rqkhbghy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2imgrwykl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqbqwgoo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qekfbmyv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtcrtkp.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzkbjrr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ewdahkku.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2gkaurbna.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qaxymbte.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2dmmpirwj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2pzxjnewc.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qtwrwwot.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2wjifbksk.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2idffqgjb.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgvmtet.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2pdqdegbd.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ftylcwnt.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2hzuftutx.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2phdoavwx.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhcwuhg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2netsdlhm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2beditzml.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyhekfug.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hvkwoost.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ppncmalh.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uklrzwkz.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuptefy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2guzyrval.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqgptgq.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfccrfo.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqltjewe.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cviijkik.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmdguuz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtsnsay.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2afhhqcun.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2lcdyqenv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlqkxnk.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vbrycyhw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2syqzdxxy.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uljrsguy.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bvdwzypr.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rzwztcen.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zbznlvgm.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2kuznqqir.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2dqszfihb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgevobq.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qviyssnm.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2vtuiokkq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ccdczwgu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xfuvptdt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2yfodnkce.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ytsyylzh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytpfbzzr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2myhjhmbv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lxsaucfk.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2yomcpwle.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pyvwuagb.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhnndbp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2ksxtrptf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2xrjzdurz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zqfhkvhn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2uzulnmbr.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dfeoczja.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uukltzuu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2nctijbuj.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2yggrjeyv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2iwncolwc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqhrlko.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2akstuodr.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2scxtevlz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2izsskwto.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2taehquky.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2jankttzt.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2qjgupamx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xcirknsf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2snpmllyy.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2lizdytgp.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kenupefb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2khkttdrn.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dovahkil.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2idvkhlxb.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2mxgrpjiq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ezoovibz.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2anvwrkgv.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2drbtvelq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2heekwxyp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uogxmdda.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2appecirc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2totcwbvb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2npowqmlo.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2frxjcygx.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkrkgps.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmqhoxm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iczaqihx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rahqnhoq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qnfhkzbr.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2kapjxorl.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zsjddjpa.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpphefs.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2svaspvig.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lanezvpf.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xvrmoqcu.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2haxmylky.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2epkszjke.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2zlexorhl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2svjfeqht.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2biqsiufv.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2aqdsrtww.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2zqsjxggl.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2bnupbwpq.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2fsonqoiv.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2llwxgncn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2wzoecudj.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lcvfntik.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ezfqwbmv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vrqfizaj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tstamcqd.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cvdgqkdj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkyhjxwv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2eydzwpmz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tlxfiawb.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2xauusoqc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eaqtfjtv.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2spnuadks.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjgacei.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2agaqqjtp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2izdhgvjf.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tuduaaur.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xlanhttm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2rnccknvk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2tczbdcsq.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gocskqth.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2uixrinzi.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2zmynefvx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2iaftabjl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2qqnimnby.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqwkvff.html


<!-- 参考信息 -->