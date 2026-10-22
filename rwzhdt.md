代发 wailian999

[S37] C++：set
来源：http://dali.zhijiandao.cn/Article/details/gt2bdfegiun.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2mnsqdldj.html

[S38] C++：排序
来源：http://dali.zhijiandao.cn/Article/details/gt2gvudwdag.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2jlcakmjo.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gt2vpflapym.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gt2drihizwn.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwpzeov.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2iqeljdsn.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wucesfjs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqdzxwm.html

[S42] C++：继承与虚函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lkyynqzh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrksxdt.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2hjufbinw.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2snoatzzk.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2isfzqhrv.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2joxqvmmy.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2qxauiymp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyczsoc.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2fxnggsnj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hfuovhaz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gexgowgw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxlpzzjl.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2luplenhs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2dykhozwk.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2miwbdojm.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2owplewye.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwyqhgl.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2idelmvum.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcidkmqa.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2quoshnls.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lgncpyld.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2lzuuhhxs.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gcfdbfdo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2yzeedagc.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2obelkdrm.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mfzdcgyk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjxkbmb.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhlzxux.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2mafftcuq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ralivlja.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akhllumz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zpywlhlu.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhzrvmla.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jvstxegu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyistet.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2dvuryyri.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xvpngvuj.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tarlstgt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2qskpaqex.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cwyqirua.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjohfbc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2brfgqmut.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2wkohmnrw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsteyyo.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cujksesa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2zjjmyuyv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2irqkqjuy.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbfjycnn.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsoamki.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2zrjeqlir.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qclmcoay.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2pnnbojag.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2byzmuhmb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2axgeaucp.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zbiqrred.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cafyyypt.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2zfdnprlz.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cxeoopti.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjtfbdk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2cxotycfk.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfbjdwk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tdqlycjs.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2eblfssxh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2lmrgaxyb.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2ribpiteq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuqllgxs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bftgtbuk.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cscpfjmt.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gtaomquf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyyjesbo.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2xmrltwba.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2saygxucx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2iolkwmhg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pluzxztp.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2iapukwlp.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mrjzxnao.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2odbwfsul.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqfvvwk.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2phnehdfw.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lxvwirrq.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mjczdkjf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2jtndiohd.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xdztymfb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjpwxnh.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2sjovhjaa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fpohamln.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2essswbad.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2xyhewebu.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mfftdcco.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rxhzicsz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rkrjmjcu.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2cguzsmfl.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2ipawfprm.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2agqlblax.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bscnwbdp.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuodcwk.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bospwrax.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2oedwnthi.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2kufbdahu.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2jaditsxg.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ivzwsgrc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dqvnndlp.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dhprxlyl.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ncermeeb.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqmqymtl.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2yacpjvdm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2ekogesag.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2axbtwrdj.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wrqzzjwn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2anpejvkc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2gnelfhvh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdbhecb.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wpshzicg.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrfeavg.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2gvxqifnn.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2muwphveu.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebyzdswp.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nuaffpcu.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2mcebcqeu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvypnmj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2yhplqstq.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ewugvrtm.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhhkfso.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2vynhrhxz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ujfydxph.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qpdozsdl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dxozioeo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2adqdphaq.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pdygymtm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tigitoua.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gvsrcpwj.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzjvxjpq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ypyjuevu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jtkpwuyn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2qqpuczgd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hkrlqszh.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jzfpjnxj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2rlrpfeyf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ybmydhuz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2untnkqad.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2denvtnvp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzewevuo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrrforo.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ratpkkkt.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrphoxi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vyzznucd.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2aqyzvjcz.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ormjewsq.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2nieerpuk.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dkceqyfm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2msemkgrh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ixbefrkg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hddrzgjk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2zjexyfvo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlhlxzf.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kibidpyy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2glleczrq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2sxcjndao.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2eezonwng.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rhvepxog.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2gvlqeukl.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2gshircyc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoignvd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rfchkrxe.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2zluqidjp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjledsnu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2msamgytq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2hnrzodua.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yutgmgdh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wdrileio.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wpzabrik.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nphbcpab.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2bgztrvtr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2ddnxbmot.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2atgompgr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2gzsorowd.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vzllwxxj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2xkylyjic.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2pdaedryz.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tpbkolnc.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2thmnzlmn.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwfojkq.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2eqbkqwjr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybguhpad.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kpbifwco.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuppgylm.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mfyormxm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hngtcgxq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2pkpnylwo.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxrxlwtn.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2twiilbfu.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2bsqvlpnq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2mjegwdkz.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsimknn.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wehfoupd.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbtozds.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2nlihsadg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2hzjrfovl.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nhpqrnlz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqwtzcbq.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2xtzgusnj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2admzacdt.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqmqvxb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfwvgrn.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cyqdwtms.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zknyvxue.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zikztyoy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2myyrkuuw.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2apkcrxwi.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2wzjkrsgi.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxhispzw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2szqkmfij.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zuycitsp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2kyrrjwww.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2myhmaqib.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2oscucrob.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2uejoyyml.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2lvjjeucz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2copvgirx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2nlgjpgla.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mkavnmlt.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zlumhuxn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cziilfch.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2odqpevis.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2jutelqbu.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2duttnpmq.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2tomyffcp.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2phuvalsj.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xgmwrkss.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2skvrywog.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2bptcnenv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2hmqyhwlt.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ddehaomh.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2plfxkmkp.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2sjzztngi.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2vgffslek.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhkmhbw.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2hxjhfife.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2iehcskcq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ltefkszi.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2wtifrrig.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2patqyvrs.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcjkrzo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yymkiymu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2hqiggmsj.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2nswuipez.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2lkayopsl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2oqyheykc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2vncqnkzx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xkrfdelx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2egslsxqj.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugxudwem.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsmjidyc.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ceggkvqv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2iimdtwfo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kmunbmou.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmitwxhw.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2roxgtabq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hlfjiqmc.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2iwbbisjl.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dztfpkhn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ujkxloyd.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2lkdyypiv.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dirvlspr.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ifvmoiir.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2pxikjckf.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2shsimjij.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2eanlbbfd.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jacodxnj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2kosnrczs.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2udqwsust.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2hezwkchx.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2cgqdyjdl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2expljmsx.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2wslohxtu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjwqfzm.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jpxiqihz.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ayjoopiv.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpnbsop.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fchurtrb.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ivuqowtg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2mklwnxxw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fksxlntf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2brtmxkrd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jsstpahq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2gzabdwwg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2dloxyxdt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zwngkaoi.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2tjfhsdcw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvrneyen.html


<!-- 参考信息 -->