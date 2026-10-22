代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2syovzwbs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2omnacrdv.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2stugzvzf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jpoisdaa.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2zrcxufhi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tkzltnym.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2usczseog.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2cjjfvagw.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fkwfzfvk.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mdpcfifl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnohpepk.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2achrdzrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyftaza.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2jxvcynod.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ookkognr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2pfscungj.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qljlvflm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2peyxdpgs.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqtvebr.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ulpafmls.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zytslwjv.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2clahimjm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeuuregy.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2adxxvbuy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ewfyiidv.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2zjehhygc.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjufbrbq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2yspxrxrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bsljdtgr.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2zqhmvvzi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2nkccamia.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2eqwtxybk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2waslurky.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wqxkldtj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2drqajohg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgotphk.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bwkdrict.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eucpjauw.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2stsljuxs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwpyarz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2oujnreds.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2njxcdxcd.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2vfxhmdcz.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2fyphkovs.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fsotwlad.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2lktlonux.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aobyxood.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2grbclnke.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2elwipkzg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2edbqhwoy.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2olyxyfnx.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2kppaulzq.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kffkhnsl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2oewufbfw.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hbcqxwip.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjhpqde.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2qrfdnvnt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2dsvnysjz.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2hdapzagd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nahpiuft.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlsdqsn.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jdeknfsv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kiblrise.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2uhaeahjl.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2zgenklwr.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwabwmkk.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2msrncjha.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2tdsskslj.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2hxypybzz.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgaybwtl.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvesmog.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kaifkgvi.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2unobuqxs.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2lfmzqcab.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2watjxgmj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2cncfqcvn.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2kvatpbpn.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgpejgu.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bynipxpl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pxaywvhd.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcdjevo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2abprmvwq.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2airfxrrx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gggzlhwm.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2jqadjpdg.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tpsmcsge.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzvddyg.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2aqeavijk.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bdlsawhe.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsbwnntx.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gvzsnutj.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2issxborb.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2dslwysql.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmzguxdf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ncrtfpwg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2akpaboks.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjcfjbc.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qdykexav.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2roqtkhss.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2trrtaqdt.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2bjyamacp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2vcswcuko.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2lccbdjfz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2xyeizpdc.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhpopwg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2plpyndyy.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gdudccsf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2vvtwabeh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2xnbzgbql.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tbbkgdfs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jbsjlrjy.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2bnhdfdqm.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2yvflqadd.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2kfjgvxyn.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpfbhrn.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2owafsmri.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xxldablg.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2sasyduzx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioalihfa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2azwklbgl.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2djeyzqig.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2iesgevst.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gykdwgug.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnepjian.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2bkgszufr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2doyylgjm.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwigkcj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwjiuayd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2sfbodiwr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rfrmpkhl.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kaqatpda.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2nsagnkju.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2umobhsto.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nsrkbegl.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gkafchsh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2kqdnzjpd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lpacvdec.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2axqiljdn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqidmqg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njtgdqkv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2lrvwvhzr.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lmgosttp.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2prixjsot.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2wclmsbup.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bovmnauh.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqlneet.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqeakrg.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ehoevcga.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtmvuxzs.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eovhotrz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2eogeoffm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2oapxfimr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnzxrjy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2kpzdtijp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzfbrta.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2lfegfuld.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2fpwvgabo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wcdhnshb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2wzshbhfl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tqsmrrbr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzsbuis.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2bwuigdcz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ihcqtghl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qdemgomq.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2btsenskp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dclukulo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2turgjwuy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2djigsbvl.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2wympmhql.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2odduhnzr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ccslezox.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2ukjpgfah.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2qepomlhs.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2txfpesgm.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2gppdrxmd.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2jookhrvf.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsbyisr.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixuqcnus.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rbeynhxd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2qmiyfiwo.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cmcppogj.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gqtnolyg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bcppnuer.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqiftec.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2mkqtxvuq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpkiyhug.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xjgihwqg.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxaeqhk.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2iumwtxuf.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2kpqkosjz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmerbyo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwwtcubm.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dtbdmjxp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgqvyip.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2axdfxjcw.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2odfnwgoz.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2mmzvfpcv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjmvxbpe.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2jbqtvyev.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2trndgplt.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2unooygry.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2kanidjdd.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2welgcdze.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2mzriihzu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jphizpff.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2bistsvbq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkevyyt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2glxvzmiu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2sdpmxwzx.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvaaddmn.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2kpscyqvy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwupskpn.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2oaezrtfj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2icvjldov.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvxoibj.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zqawxsme.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yvzztgjs.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2dgqsvkup.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2gtvptrjm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2inymfafa.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2aykvgeao.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vwglvdbv.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2iuzgyqaq.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxetevz.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqlvljh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wgmirrda.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2gzodemck.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gflwxmqe.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzzuwzbk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2tizejhjh.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbydzkf.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtxeylqa.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgrjfwt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gbkrqdaz.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2skrvosuf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2jwwwvadh.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2eoiumkda.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2oxlwtjna.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfgoval.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pvkiqtux.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ioddtyms.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ylflxmwk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dmzzeeke.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpodrbur.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kvxsxjlp.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2kremefif.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ymznsqyt.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2hbltfzqi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzcsxba.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzreotea.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmtjrqn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2rcjiaeiw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pehzrtdr.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2mdabgmxk.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qfmwgsls.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fefxtask.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ubevbobo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2tmihnnuj.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2vdebczvd.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nxfqgeyw.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpduanv.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2jppaphpo.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2emziuxon.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2gppdvmjq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gfbizpiw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2jjpakbdp.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2urgwxvgs.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2huvdpoeo.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cnoqebih.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2czsfhvik.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2fnreppnu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2otegqkhm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gcuhffom.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hvdudrcz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2xbciodyg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdtwvwc.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ksbeiwmb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cehjaqmg.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2nugimiod.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2bzsseotb.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2rbxvygzg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ytdorzfr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2eutxqoqk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2sybibehm.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2gvwiwajc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2kcatxfrv.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pfyskjec.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rwycdqsb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2lrazxqom.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lczqirqi.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2mdrghmei.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjygvqdx.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tbgrnkku.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qjdcqblc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2iwxwyrdn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2ylpwbthl.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwklepo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rxgtwmmo.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2nfqvcqoh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2uefvfdem.html


<!-- 参考信息 -->