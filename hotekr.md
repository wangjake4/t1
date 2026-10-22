代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qsalklwf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ywryrutj.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfrcdoi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2algwmctt.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2zfxtfjrt.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2idkkfbma.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yfgoxboh.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2waiqtfdb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2rconyooz.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dzxfryki.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hirhpbwv.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxwozoo.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2llvhegvz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2quawruce.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2eqjxtwjh.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2quqwhulr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2wiqbxxhz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhdmabg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ecsuhfit.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2qkipacmo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2inosujvj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2tkiuuatr.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnylresq.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2eagabawu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2bcxhrhmu.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2eckftkkg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2iktfwggm.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2wbckmomo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2baoqkefr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zpqxcfmq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2uqwxocve.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nekwrbqr.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2omjbytfj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fgervhax.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vzeizdve.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jkqfoyyr.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hufrybzw.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2frbflvqc.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lhxrdxsu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzjdbyh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2kqzalzyk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2rhkmgfie.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjmlrih.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xikzahus.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvlwknd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkpyrdcj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2ocbnknjo.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2imclfqdv.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2efmzypys.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhjidlc.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2amkpfsnd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2atkbcqmv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2nuzmhpoz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxppeent.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nempsjcr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fhrnzubn.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2vgyqhahx.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2qbphtcsd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rkxmiyoi.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2awuuegok.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqiofnd.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqpqnqr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnkbdnf.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2snommezh.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2ejbzpdxr.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ahfehcbw.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqvggjsz.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcwvisw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2panwlikv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2vgrhhnqp.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mzasnict.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qefikkrw.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2fkzgqnjh.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rpzbhxox.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2juwxpgsq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2pmoxrgee.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xaedmakr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqbdkjc.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyxzbrh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgylmcyb.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjulfsi.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2evnsvjwp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2upjtymag.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmluvuvv.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzdbivw.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2onjlwtyi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rnzryyck.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2tinvjwzm.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2hyyejndx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzafpuby.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2pdhfaqpe.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2wcmphvku.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xsizfpqu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ubnbtspo.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2azjjowuc.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2vbfrqvez.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2cvhkknoy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdsrgzs.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2bdcktuko.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2bgxmoser.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2idualhdq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ahhxqklx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtfrjsj.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2tmgvbhuh.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2nseoqdvm.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2itjkszvy.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zlljfqts.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nbwjxamf.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2kjllfwwl.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wmsliusw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2tcsdrrlf.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2aeywmkpi.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ikqlncny.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsomdoz.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wbwkuvec.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeapbgx.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnjjjzo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2vupstwct.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mcidpyhn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2juwgegkr.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mlemictr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atxpwyuf.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2lgwvkodb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obsjptgr.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2dgcggibe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdilqgk.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmdtzag.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2scpdttvb.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ldzlvrxy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikvilfop.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bzrcjxzp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qlredwde.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2krqctvts.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2xotpyjci.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ypnaqhun.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtnhabzh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlpzlya.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qgjcrmxy.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2pjxvhuqv.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2htotnndt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxsvvpy.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nempspts.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2zeashoji.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2hzkadkzg.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qowwghyd.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fjtoyejm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2lqlkjxnm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2gkicqxgt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2rviruuen.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mtzfmtbr.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2avbyblvj.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2peqtrsak.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogukujtf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctwtlrpn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqnqrnt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cjxmjnfs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2oahwsqao.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2swhwxyvt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2yrphcbkg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2poxdyvyu.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdkjsvp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2vwojcsiy.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2kfswtumz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2pnwuyydb.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hxocaaiv.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pxiaagfa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cszvibba.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rwavrasx.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ccsfdlsq.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2laoklwjk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2lqrtqdbc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fhuwqxcr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pkfpiicn.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2exlngqae.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dscgbsea.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2cqdlzsaf.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2qyolgqaw.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2egkijilv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2njmvjmqg.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfpdqjr.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2cvzwbnla.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyejemx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kemrmjfk.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzhlmdz.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2wrpzvqte.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2smhimhzt.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2srtlpkga.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2jqnztvlo.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nmxhsdea.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2qjamdhjo.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fwxybffk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbstnci.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2esetfigs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2napcvolu.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2esttrfbs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmikghi.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2xwqgcidf.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2naqluvnu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2uufyduwl.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2jpjiwhxr.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gqlepxfj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qgoqgrlv.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2faqapqmx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2upvseyfr.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2yerczbte.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxtnxou.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2vwebyfis.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyatnrho.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2yshuqhyz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqqjlkq.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2npustvrz.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2zrhjsmtn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2sjpobnfq.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2lepatnox.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vboervqn.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpsjpvv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2takagyec.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2vvfudwso.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvtawcnl.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzrcabb.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ffbgqsdx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2enszmffy.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2ogxclfek.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2wdgxmdjy.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2fowqlxfk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmholsd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cashrugc.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2fzrxdcfi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2czmjfcty.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2eogudjfm.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qzpskmgb.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2psmwhkce.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjzmcyl.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rozrzhjy.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2ygljmhrs.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2vjcetewh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2ztmcmifn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwkgzup.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2xgnrgifd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dteucmym.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rhgkapgd.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcthdku.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvezqsi.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lyzfyrxw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2lbpekmwt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnntxbf.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zuwssddn.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2pnacarum.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2swiljire.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2todtkmca.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2glauqqmg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loxtjdqc.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2smvhcjwy.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2fjucsgea.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2masxrbun.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpybgoe.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kxvxotck.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfwxwndm.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wseoklhd.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2wznifwhr.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2cbncyxrw.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2qyawxhab.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2bdjbzurr.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2udrzfwxs.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2czjkspvo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2wbjuwske.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tesrqgvr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frdjajpq.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vopdvhfn.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lwpkhfuv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wtsfcjwz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2tbamszjj.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2eqylhbje.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbsqijb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2uihmjcos.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2szfdukbg.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2kdmjsksx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2rirfiigl.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pkwkqvhz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mzhdmalt.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2wwwxgaho.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mggdgeay.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qunmkgim.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiavssrs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2rhbppbsf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jgsfqbsk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2scvorfvq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rhakjpmq.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2uxqljdub.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2vyqmqhpx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2byigjqph.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2gpnvenwa.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jwvlloux.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2wtmxbyhk.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2htfjjtez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2idxfbqpr.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2uaeywvko.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsutvki.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2trfoqxxl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2onmdvhng.html


<!-- 参考信息 -->