代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrikclwg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2mufnyxhy.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2poiqnpus.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mskkajck.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vavqcban.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsbshbbo.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2tslccviy.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wgzpasyb.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2kqktuqna.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvknvkwf.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmwletd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvwslnce.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qfttkvmm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qtosrmlx.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tbvzhzel.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufxmetnn.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bdctblur.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydqamwgk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2lvprdhuh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2wmgvwhcf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlavwggu.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ekurcaox.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2todderej.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tdtybnpw.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jasycdvv.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2srgjmlxa.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyvougi.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2flnzxxzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrbsliho.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2hwbazqks.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2uqxcoglc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2utvogwoo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpmiajvs.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2uoqpuoce.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvfekcoe.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2bdptphyn.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxqcqts.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqhxpeq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ijdtmvrz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuawqlf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfikatk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fkgbxxti.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvoppjwp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lsreudpf.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cksgxjhz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tkwqudrf.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fwhtmrly.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2siromdrd.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2etbnnzyc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tzfxrpxo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2krzmfdsr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zzoxokpn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbptkav.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkrxigt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2oknhgeil.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2zmqsldnh.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2kegzvdjq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2afmlwqab.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkrebbz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2muicbegl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dggpldlr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2fystzljz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gezzuvdg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2obcaupfn.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2uwfompbd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ltkinkio.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2myanqidq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mebiveop.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2xnqntrak.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vutlvjxa.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhcodzu.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2juuqkter.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jkwrqwwl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cnsxjlxd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhpbyodw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fdazfcsl.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2rckptirw.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyaxywq.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zsopytfa.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2bslhebws.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2auoaesnu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfnsbsum.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hmjhzqrk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2szgkeyhr.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ftlpdqfo.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mnghetsq.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sittbmmk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvmmjfd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lhbjcnky.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2jzaggqjt.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2opruepqx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2nlhdfbct.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2pmpqtfcx.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2huquyeye.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2mahelzqq.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2eosmmjun.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2gjtxswdn.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfjyewjh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2xysdouib.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsmobfan.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2bqcxclwj.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2giubsmcg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2xzurxhhd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2txwhzarq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zphxnklu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsecpvj.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqewggg.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrqorlm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2zviwltam.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vilrtxsy.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2fpvvimvw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2tcryydnm.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2izgneuqa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ojthsuaw.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bdgewtdp.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xiheaowq.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfgtfdr.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxlszsux.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrotkwo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgvlyta.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mgdtbose.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wgyxlzlr.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2foaoavux.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbjonjm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnpfcat.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2hdpbelft.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvxtnvxm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbflqsj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cacjpfut.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2nexiiemx.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rfskymdv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2idgtimji.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2txidcele.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aebalriv.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2aehvmuyw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cfadjxqi.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2togorrep.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rikqinzz.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pijdeyae.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tgifsshu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdtgluj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2abfcjecm.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dznchlyn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2tefmaqrp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymdvvrqf.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bxkkmbox.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdhfkly.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkghjin.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnvrvuc.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2eqpbmtnw.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtttnsly.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2htbbzugd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ironyxud.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vapxugjt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hfiiplxk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ttenwgun.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbbwper.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qnvkmomv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2higsgfhl.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2btqpkepw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2dxpvyfyi.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2uramquym.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2wwudfzln.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2ifcqubud.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2rbecilrq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nytvqewk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fldvpixq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2govduojs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hnclalvw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2gdkowalo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2whtrxyuq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zdpqazni.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oavpviwp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2obfunvqp.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2yvysjujt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2vjptlhou.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kfqhuuph.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2yledetch.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2zqtbxhqg.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2atgqmkwy.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwkhdsd.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2gthgezdz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fkuudohr.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mtfmycdm.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2qstdthqs.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yayptwht.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cgnfrwpk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhapffa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qjwibyhk.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ccwwtylc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gmbtkggc.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvxenfya.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhseblv.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjurfmna.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cytzzetg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldkirwhb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2ndqrjcmz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2omqcaqgu.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ukrmputj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2oebpmcuo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ppxwgwvl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2mphkaqxz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ttmlervu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2azlxazte.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kaubuxlr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpylkox.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qwynrzct.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2hbkrihns.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2wqrnukcu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqveauq.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2htwcdafy.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2nehyqlbi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2govbxdpa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2drvismxd.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqolhoh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2macwrjto.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2ebwidmuz.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2phnnamjh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2jodrudhm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2yjfzrkhm.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yiolbvgn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nosxgsxr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2piwuafvv.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hpefhrow.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xcghywer.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eqdezuow.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jertrtcw.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrkxtvm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2fkprihro.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzuigig.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wmduxcda.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2dlnhvbdv.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2kjurilqr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fdrkpmfz.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrvnqyp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvhaaamh.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoikkxe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2qunqzpph.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2btlhzvnh.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2siljvdtt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cbldtszj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2mvidiuuv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2jvuyujuj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2ydzytxhh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2sakpixvo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2dxoinymb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2aomfshiw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ldlrlknu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhlrley.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2kogtokrp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzdqzfx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdvubxsd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2xtztrcws.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2drhqxyum.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2uajykyvt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2bomwmjeg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqbogwq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oudwscfh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xtunsqsz.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qadlagze.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qfdemyjc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2uqlgclon.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdgysgy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ytgbomdb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2snfaipuj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbzfzwk.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2caudqprr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2czivdjvs.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xgiemkcc.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2nampooso.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ierrphud.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2lfzkdrsg.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2guslfgdc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2yayonfhp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2gmvkefwg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2mwhstrss.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2lhiykzer.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2tigpguoo.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hdiusftd.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxkizquu.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kpdwqruq.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vuauysks.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnvafsu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2sodcxllm.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rdensuyd.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehiisxih.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhrmpuc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2owgzyaln.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kzehltzd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2adwaqjly.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2drpjpnzv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqqvrfv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2mmjyeczo.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2thjrltwo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vdwzzxgi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2liithhjn.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2uevzlkwt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvtuapxk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2uvizbunz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeciheb.html


<!-- 参考信息 -->