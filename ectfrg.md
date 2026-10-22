代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqffruk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2euphfayf.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2stqzoxix.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ykbvldaz.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2uzykfmsa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvvsixe.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2igmuztnu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxjazpg.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jrlrjwzt.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2hwqovfyr.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chtsdeqo.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2didaexar.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2meyacvme.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbrbijvx.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2ssuylmlm.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrdzifht.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2joqlqqyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xfelqcpb.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2lhklhpdp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ycnlivxw.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bwohngqg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uppiimfx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtaaujnl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2hyduyuof.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdpikebn.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2isygxwgh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2zqoinmqs.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2oauquxzd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2prvrylbr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjtsrfs.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmtgzrz.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2uuexahyx.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxqcmgg.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsaoiae.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfvdddv.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eucqdebo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2atbtfger.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2urgsicry.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xafcdfhd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2wjyhgxzi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2knfkcnhj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2pdyusmfg.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkrmbtvo.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ijlmtukm.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2blizsdhl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ycxhsewq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2bysbrlwn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuraifp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2fvdkpmbb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bdanpfce.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2irdrqyxc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vlapczvo.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2adfudoux.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ajapuzxz.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ghlxwdru.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2ayameziy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2jofowrma.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bahdkevr.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgfiewx.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ogybebvj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xztmngfj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vjvkyxig.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2nomjmxxv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2twqtmpcd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xzzidzea.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gesxtixw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lzphmrcu.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ptembvsj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kepibiww.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2udvsyudt.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eocnaxcl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lquagfbf.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2wjidwlux.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2gacqcmby.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvsostq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lngatuom.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwqqavq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmbpflx.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gmklbogb.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvvslpe.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmwfkak.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hufmeusy.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2agicwhmo.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tqterhjs.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ojonqbxi.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2uznfmlfe.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kizglxoq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2rfhredua.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmbofao.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxgaqfah.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2grjzhoka.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qxqyvoog.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wmiqziax.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ifmnyalx.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2smpqizkn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dgnoocdx.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2osbqhokn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlxbqec.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2trjkfamq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ztgkkuus.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2fnsnswlr.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2pxgcytsq.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2trenwgzb.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtkyysfi.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gmdyzsgc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2edibdrmu.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xynybhsz.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2znxjkalm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2tamjsxbt.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldtgqmxg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2twlsdwrs.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hendqvsi.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wqynshyf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvishrk.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jrbxxbkr.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2axncbtfn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2moxkthin.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rnrjrgav.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jaluehsw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2ihpupfxy.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2cnndwseu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fblqkwhd.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntihmmfi.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqpujkb.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ydofwugb.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzmesjw.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjobbek.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2zhsfmuha.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqpjveb.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2knusnmko.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2rgbyrwsa.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2dsiimdzi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fywicmxn.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sfujulht.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2siaiskbs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2whirlili.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ctemumiw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcbsmcjy.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gijoyzxg.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nwtgsnsc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2rroznqib.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2elzsizdt.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2vriwhuqm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doejdwfw.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnkorah.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2anfhuuju.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jgxzrlkv.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqaskch.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uuyrdkdi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzqxwzeh.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bcwfoatv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2friwrazh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eorakzjc.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxgfqbu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2iubojgjv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uyricjcp.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyixjte.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2axmeudut.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xnuxuxbj.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2tgaigndh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2lmvhfdho.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2oywteoyv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2dwdlzkhk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvejxlm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2alwrflkw.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mvuudnzf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcdoyvi.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjkzbgy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2aotfzlke.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mikmltdt.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsywaldi.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ukvlaibo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbkvlbo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hhtxopbg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2gbeeeddp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eajmdzyr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgeokcj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2jkrljyau.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2txibbzfd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2temkklbv.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2bquwasdm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2urfvzwlr.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kxbsjhqo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvtxpab.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2dcuyjznt.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vytwwpjk.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yujatziq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkwsugh.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoghwyu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2uceajoop.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ktlraydp.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2czvokufl.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pxcrceim.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2wecopnly.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bdzlowdm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2wdlxhghe.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2llgazsbl.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsohyopd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xecmkpfk.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2lnbfhepy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2sfpttrtl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2edlzjygj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hnicogey.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpelvef.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2osaljiaf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqusmgk.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2urzrtdem.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2esqvdkys.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpajsae.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2kqhibbiq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbzrmjv.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2mihqgvdd.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnqysei.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ollilxhu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ycvonrpn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2gnpwwhul.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2eawotivx.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hftypjke.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2zdskkipy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2uzftqsjn.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sytphyex.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2txiuhhjt.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkklrti.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgxooppa.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2leefnner.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ioweqwpy.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtraxwf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ipblkwrl.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2kquuxxtc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2itzioiez.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2diwqidye.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdppkdi.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmrrphy.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2hriwtbal.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2bwnuslif.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2paxfklfw.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2epupbbcj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdwpxkr.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rjhouiky.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuhmpeg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2aswcjdmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekjtiwcv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2msfnuduz.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ssfkccjo.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2imallmdd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2xixosygf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lvszspmt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghmgjpjw.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjdlsbf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2agptabhx.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2vkbffpms.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2suuuuhjz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ytuisgkv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2fuuxhkpu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ihtwpfbd.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pwewosli.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ncvjnysj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rymcphvu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2lloyvydh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtedzuyt.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2dmswzhdr.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvapxjyu.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2usopfidb.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2sgxfdbau.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lghryfdc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kjipzclh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2upgtqajf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2mjigygyx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mvgvkxbf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yljxnqyk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2btaoylpb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinfgffg.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2unojhdrg.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2qtllmveg.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2knfosrcp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2gmmduzfd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2nugsaksy.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2zmtugeee.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eosfuygo.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbvncvwt.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2rscjajzl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2rlgrbjmi.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbtrgga.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2bvblevck.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxruwrt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2oehkuamr.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xcnwgwjg.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqfjube.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uafnkhae.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2npgcaayv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2fmxlkwjv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2reshmznx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lvkqrjjh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kvidddgp.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2gzpdnrnv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2izbuxqmb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2mjmbhqqu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjvoggoa.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tleayupf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2gkjsrpmy.html


<!-- 参考信息 -->