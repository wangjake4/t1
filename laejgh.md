代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2iwiihvce.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2yxkpogvd.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxgcytt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yitamzdr.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2koyzmeiu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhwhokw.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjvedqf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2fakjlhmh.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2uexzolqu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hvbrcvsa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxakrmw.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2stigfouq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2jegxntgy.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucwmetrg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxdboao.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhchxml.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwgseoo.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrnoffx.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqkemmfh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2unwwvloa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vibdigya.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2mpdsyrzh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhkkfwz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qxnztjmn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2klzmgawz.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmcxuva.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2haburjsv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2pztdbgwe.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhlfmlub.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2hckkqxyf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2yhdhespv.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2bdwhilef.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2gzhdsjvt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2uamascdt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ztofdwyg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2rouqzcem.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sozmebni.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2oqchlkgl.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mseccinx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wrgixymh.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2golgcvpz.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2brbutkiu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2mbddomig.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2wouimuvj.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjnfaoz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xemxswqq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2omjafjiv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vjamtbbr.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ketcnnme.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2hzbgukip.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ivbktxby.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2lidjydyh.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2opoqrrgb.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2focgtwmp.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2igoqomxd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmmpswhq.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2vborlupr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhpaklny.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2borztpgb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ajbiofhv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2hgywuspt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tdmkazdu.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tpjhvkdx.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylvgonsr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmdbayn.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2svvownhb.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vxjsnvfw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2bcszqcaz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nqdidqew.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ffnpwhtg.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qyilohyr.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuumojov.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgkwgbq.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zuvaseuv.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2zzdnyhip.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjoikyzl.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2sdbfslbb.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaiewgz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ceovlojc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kbfcgnlo.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pheaeadz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2bramjbvn.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2bjvdqutf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjatjnx.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbiycpb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgvnokjz.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgnkxdy.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2glsdwecw.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ckddjczs.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2darmsmzr.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtyqodu.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2roesdzem.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2vizrqlyi.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2mpomhapy.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tvswtwvy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2htoqyocu.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqdqbte.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2klofuvho.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2grpgrkpf.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2nvtemxtu.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2yqjsrgvj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2euuxoifu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjartve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2cpqpwcde.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2pnuhgwcj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2wdxxpnuj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ynivzqge.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2hbclxbjh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwigckg.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2wznxnmqa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jrivmahg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnqxnkfg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ycyodxqr.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bqdfxaza.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sgwahzey.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2egoqdqbs.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmgyfdo.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhdmobs.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vndyngnv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yuxpjsuh.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cczybwct.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2pqcbkwov.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmktnhqe.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjlbqkw.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymowztoy.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzhqhoda.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pzdqcuaw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qqbreyby.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyqsgxr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnkicnww.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnxvons.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkwkjkcj.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbmkscd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iyniqyng.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pyquuphf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhfaczq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ophqmxte.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oaxbdyam.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2eoeifugm.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2niwveqhl.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bgutbvce.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xphramnc.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvxblsmn.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwdmyfq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2solocpcq.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2knuhwbgd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gecmjifa.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2dveojhim.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2exmezozr.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2welpflru.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2uwjnjlgr.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dkgwfkmr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2oxzyywpl.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2xaafaddz.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dpxupaga.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2siawituk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2geajkduk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2igyxcneq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qrtlalrf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ujrnsuoy.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2qqcnnqep.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ewhuidcg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2zwterpze.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jalifevj.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2mmijgktb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2yrzyudou.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2toiqioxv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2rykdeqrr.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2lldcfnwg.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fjuosdbx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2difssmpj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2joydbowe.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2nhwkzdte.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjatuah.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2tpypzxkq.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2pnsnfrdn.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2siszwbuy.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2xdwnucwm.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2tzpomzon.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jkkozxgq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2orhsonfe.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2spumllaq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2tfntlvvy.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjdcsts.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwgagym.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2sgqvyivj.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2ypeavzve.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtudklqr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2obsbcdzb.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fbxiorte.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbxbael.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrrkpuym.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cdeblcwl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2brrfdxup.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2lahfdvqe.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2bspgfyly.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wxeqiqdm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tuwcmjtx.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ngfyetha.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibgjrsuy.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2jkvpzufm.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfpxxja.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2oyiuowvj.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxdkzgu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxwsdtz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2eksdnyco.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qcscbvni.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwuucfo.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2dhaxtvpf.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2wsefjlwb.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qkjfmvkm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2qwetnchr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dcmeqozc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2onfjgsqr.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2tecdzjkk.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2uiisgzws.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2znjpkhzh.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zfgiuwur.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2qkiqhrvd.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2xuypktgf.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ianpwlgi.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2leunvazo.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ayqzsnqs.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2ygbvqnjj.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2iapdrtyf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyyvfzh.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2spujbdro.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdkruln.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2ffgzfzoe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2jcihnmcg.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2fsldqbdl.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ehlnygre.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2bcinkcpn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhjamsk.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2bnyplwdy.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2epdzxksk.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ynvnzwqe.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdypdql.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2tophspvn.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2koitqqhp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bhyqvbnl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2upefpeez.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2qeylpqqn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxbmtdx.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmqpdsg.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2efpyzxre.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qkbixpie.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2phrkxbar.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wsocblqn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqlecrm.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hzxttbep.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2ykcjjpob.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hfnlgndj.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2zdlfyczc.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kuzlrlpa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjmgmtdb.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2dqkgrdxk.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjmrmfb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2etwpuzzr.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2azcbliap.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ivlqysix.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdaxlllw.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ddizxlkd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2twjqoiya.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2johxanhn.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2kkkbxdfg.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hzyqahfx.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2kxflvwzm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ibumacbl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccvdxrzv.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hcwcbhbj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2rxsxubty.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2ojvfyios.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyqwuva.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvxqfvi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtuqicpx.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2rpwecckv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwmolhtq.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xblaajsm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kbhixacp.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2wcrsaqqt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2ubstsvym.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2upqgntrz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2xzexgcek.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2elmldjhb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2uaoopyck.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2revgxsor.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lpmgtijc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2nbpwvnni.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tizzrebb.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2saisbreh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgxeffwa.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2tpmsottx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2qrropvca.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjkrylad.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2dfybjwui.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2cfjpbini.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wnsfnxxh.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mlxjwzjd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2omiiutgd.html


<!-- 参考信息 -->