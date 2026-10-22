代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlfpnhj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbornpxm.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gbatcsfh.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2svlwqpnr.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2pbhzoxbm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvlawrv.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsbygxg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2hejfzitn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bwtwygos.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2wsqxbesj.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2cijekucj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2tgqgtwlm.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2cfowqsry.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2ksghvdta.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2kpweqpjm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2islhduen.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2wuwpcokb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2jvvfhwql.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hhesmgdn.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ijaulwql.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2enuvrdsz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aassbfio.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uputbbgq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2zidotwvr.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ihixabmj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tzlwqjyz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2abhvwbgl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cmibzfro.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2ximuqyhp.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kwzqcihh.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2moanxrvp.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfacmfe.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dteytthj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2slyrtqsz.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2oilbsqsq.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kbgtatzt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvcuqjp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qxngbpox.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2syszdryh.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2haugnblr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fylgwxss.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2krkcozrh.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpqutfu.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xdmlpodh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2tsdfdasy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2bquapywl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2cqsspaki.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2vdmzvxhw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uaxhmdlh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sfnwygos.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmstlrd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsxizxg.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2acqoataa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eyzupujv.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmujsusv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsisevj.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2katelrqq.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvdtdtr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2isuodxab.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2laszdecy.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oyllxmip.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xajddunk.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pskvticw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vzldacwx.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tzkklxtb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ixkzwdtj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gkqqrmlj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hokuyonu.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ooakpzgr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bepopayh.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pttnoajh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2aonslwkj.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cuhzlpfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwzojxk.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2jfgsvdkl.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2tmmhbfje.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2gylaaxvp.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xectrvsj.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2byegctjr.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtjyrdkz.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrmckar.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2krzgskjb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2kcxhvuqa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2vqzdccav.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfzjlyc.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqzhdzc.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2yvqqkfxw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxheofj.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2bohgutqb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuozyusd.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjjmpqq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqhdqlbe.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cfkhgjqk.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzepstxe.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rpslzluc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvutjnrr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mbzzqfhw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2njngzuso.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2guvbqxol.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2miarigyr.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pccjqamz.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2idlvzfxh.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2wlchcpou.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2yumkxvpt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2csaijtoq.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mxaaepzy.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uqhjfpsy.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qsxuouhb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2cvynimaq.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2shcfzaqc.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2yzwbbduw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2srlorvgj.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebnnpdhn.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2djwfirqs.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azhkyyiy.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2bffaiyqp.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zqptvlrd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2ofzxfihu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2yiocumex.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ynurbwsj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2qaklbdfq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bpbytwdb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rjkjnltn.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvmutiz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhiqljv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lehwnyzi.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jgvebkbr.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2uvhhswba.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxddzmu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cajsfmuo.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2gjttajdg.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ubfxqpxw.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pnafvzux.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rxlcdtwc.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xgpvozki.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hpsjdalq.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbmrbpd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2rbsusimi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcmogqt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ucrmrlrk.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gfxlsgcj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyvigyvf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kbovrbfp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsxyxka.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bxjckbqf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrkfuzx.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2grhiqyuu.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2upqibihp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qcrejwuu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mgvxhijt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2drupxjxs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2iyjmhxzx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trhwsews.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rqzrrjxh.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2igiygfot.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dvscwpmp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwljlgk.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfeljwb.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2jakoznax.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2twjacyon.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxjocqu.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuzbtba.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2eekpbtgk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2nwvsnasv.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvwezpg.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tauerhgn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2nfpzdsre.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ebuimnha.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2yzjlkrru.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nmlvttmo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzkqvfmw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cojctdcc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvwffgu.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2amofdraj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2udnidgtt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2sdizzvyw.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtekksg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2estgazgk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2recqhglv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxlrdfwe.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2blwlxmhz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nbqekegb.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvfrdxf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqgbnra.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmcqlxq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2oeouigdg.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2hldxheil.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2tdwjirgr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcoletu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvnavyc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2zsmvpxvg.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ncdiggnn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2hyetquax.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2amqklxxi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2prnbsfld.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dywtqymk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kndvvcae.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vpoqoako.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tketxrwv.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdhxbju.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2veznqgbh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2ugfttoar.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdvqjco.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2vvstkmfj.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2exzzqsvg.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnkhzglw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2mwwmeggq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2xhagqfwz.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lqicwggf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kzizhjbp.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxnhgaz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlotsigu.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqwfkxk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2wumdmfwl.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2lbeebbbc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lipiwfgw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jaxhqzps.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xdlnwdbs.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2jkauhjxr.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uojaleeo.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mqktennu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2azblutci.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vulioxsd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2svdfykba.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmjzzca.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2duhhtwqu.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ijqssojt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fqfaylsj.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2qvajkvyv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2yleoohls.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2icfwhidi.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2sngbuabz.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rrefoyjq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2yoxbuppu.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2faxrvycc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2idxtyzfp.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ugmqhzeq.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ednobidc.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2juevgtgz.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2jzbrhljt.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ukskqaep.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2rpliavae.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mabzsjce.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2vxmziyqg.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2gucemkix.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmgldqwi.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2kmkwvved.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgfsduen.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jndpodel.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2csdkzipq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2pvwfoqoi.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2evhucihg.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tljsyqpa.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2bpemqmec.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mqxmwqjd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pagxrrfs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lnlieyev.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ulndkfqf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2jlxkslrm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2anchtamg.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2udwqutuu.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2gskzglbc.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ybsxmkrr.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hkmsrrwf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2jcpxirvk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elvlfcis.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2rgxwstir.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pgghoegs.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yynnnwnk.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2tumrdifr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dsyfykbk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rqdfdjzz.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2syrgqubp.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2uvjjmpxz.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2awpouvdc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbbsmog.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2qchrbmtx.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvxsdssp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2indkoofo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lrcucdkz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qqclcwvj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2opsdguwx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhbvcoa.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2joycscek.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ckznrwyq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jphefojg.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nsejkjwz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2byuotdkx.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fagsfqcf.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uygemxju.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnrgizq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjlxbzn.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jyydbxdf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2egvwukzs.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2knuhkewy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gwtzfaob.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uzgprwcm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zzxnmhvu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rvsrlhva.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mztxgwwb.html


<!-- 参考信息 -->