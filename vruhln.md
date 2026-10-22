代发 wailian999

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2xbqfrwxf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxfgdnlg.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2hbapfcct.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htgxlqtb.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2cumnlzem.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nyfjssjg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ygwuawbe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2awihwuqg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gakfvloj.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lfneviuq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2uwsjqtnr.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2bkkuwcvj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2cminmnyc.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2igmqdwkc.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2lyqqwsoy.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2knzhfbbm.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kzpqtkaz.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2mjuoaqow.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2dapikana.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqmnocv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2gyizaeoy.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tqplhuoc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2guabolmd.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2nrqivdtq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kyjxgeiu.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2btakcxdm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcdoxefd.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2iwyftxks.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2dfnjmyhx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2leduzoeu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qvsnrllo.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gfezbrmp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2exctblwy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2exxjmsmp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2kmoxisxo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xfhamphm.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2edtaagzb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rxkrhsdx.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vznzomhv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2tmaddinv.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2dkmtrcxj.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkacllyo.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuuqron.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ozzgwcgf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fqhrcbde.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2oxpxywnz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrpslop.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2tgjhnfvl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2cncryram.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbuvuffj.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2venqmdig.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2zsamajaj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2rwvopxgt.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsjekhi.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmjoqpv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpwwhnhg.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2cmfdkdan.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2wbktelui.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2chdjvrif.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zwoxltiy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2kgwuazdf.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2yueijtcq.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2bbtpmbaw.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybruqrum.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2blidfybu.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qrgtksuf.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hamxytqa.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2aetqmoak.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfybnepv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2fksplmdo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pdamhceg.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyjklesn.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrgowol.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dxccbkem.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ojgcqiyk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwttsww.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqqjvps.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2awaotjkb.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjomsex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxtxpyt.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wjicaecv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2svfybdtz.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2ksdyetxe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2szgwhlpz.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nhklfpmb.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gokrqpmf.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2uglkfcjh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2dbxkmemu.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2dihonndf.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdggkua.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wuadzbhi.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2qzgmkpej.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2eizzbyds.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uyfgqyas.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2bpzdzlyn.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2gssoiaal.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fwfmmnmv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2qfesskhn.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vowgwpwt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zxktrtvi.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2miqnxzfj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2kfvquror.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xoypskve.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2lvylybku.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2wztjorja.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2tjwdsbms.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nleazrnm.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxahqrz.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cjtgudtf.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mmsabnaf.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ddyjertu.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2ywkzhogw.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2tsvempah.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2zjwmxkim.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2ywtzxmax.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zyfghqat.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hscxuwvk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tzthlrqr.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cpkibhai.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2qserzxqj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kkmkvkmo.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2fqklzosd.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jfmqblia.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdqsnixd.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2wsvthdwf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2imifpnuz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2sdgmfknt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvrdnin.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2bnoxwzvg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zqbozyrg.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qfcdrdpr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2potwmraw.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eclckjtt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2trsoccdq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzhywri.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2okpcdogq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhfvdhq.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yfxbflby.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2zwbimqgi.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2yngrkbmk.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nzsvexco.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xufylhry.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2txfsrknm.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2vkdlkeea.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2pduchsmt.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgomiqv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fcdgewql.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2iigmpgih.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2deteojiy.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrrgghy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2bgobbwre.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2nitnjbqk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zngajfou.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tchlqeeb.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xnsqoboh.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2cogdlcru.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2drqmnxfz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vevijrcg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2rvklbldk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qrvmqzlr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jrluleag.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2wlfsiodz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pfnzwcvm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2squpkzru.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2omiwnezc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2gclcskpv.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2srxkofhf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sjwrrxaj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2kgsjnkrq.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2tjxgiaeo.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mqymurot.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2rhsyqrfw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvvrenp.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2psciqsgz.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hktkcmnh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2bmajewfr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2efqffflm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2jzerzjdn.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cguvsght.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2dmrqqxpx.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2vjwfaizq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2bvwibgeg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qaehpkog.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2gutnxvgy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2hlpblwms.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2anwbpecx.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xmpcvfxy.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgzyxzr.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2qrmkyiuz.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qtelpttz.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2xctlzjpo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2wmajxxla.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2roarfdls.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2irurmhmf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuebosp.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hufsgldf.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfektxk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxocwnq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2yqogaijo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2trnwhofb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqwlaii.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2fwqouxwn.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2hrwnvprf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2tqxaycot.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2azrhvcqn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2scuevxvk.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fujphhkz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ylithwxv.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qzfcqslm.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2ucuugkpi.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2ljlplvho.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2nyxgosnv.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2bkziuxhy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfijbti.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2ndeygofr.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2pkbdwwlb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2syffyjog.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2vfrymaro.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2btscxmgg.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fytmuqkc.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqetclm.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2cfydaljf.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bncozwox.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvjfxqh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2asjqdega.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2wmmljazm.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jysimdhg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2hplsyvox.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrrvlag.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fanubpzl.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hcdvvivv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2amiwbtfl.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cercnggr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2oxtjptoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgwznii.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2wklhktms.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnnkoiz.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2okowjjql.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoosdjx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2rboriyxv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2yrjctwvc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2dyquqvys.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2fmlmgirj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2smvjbxxh.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zemymdvt.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmauercd.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbiwekz.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ownhqiiv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vjljfbcr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rsdhewus.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnftobf.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2hnnkpqxx.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bwccdtmd.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkevazn.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2chuzzntg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vpodjjea.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2rnqyfyjx.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2akopjscc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2ksojsawf.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2kqrdzzdj.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2xdewrnic.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfqjnhnc.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zrmlfcsz.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rosbautd.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdfzmiv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2pvutfird.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2soctfnkc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2datkbysb.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2yrhluxwc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2amsoomgn.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2nhiaednr.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zouvuzyz.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2bntflkht.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xljlegmr.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2bljfrdmp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2paqbazfa.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2tprdmhly.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbbwasfd.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2abthvuez.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2doofgzsy.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2uagnnkgy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jijaqegd.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lfirimtq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2guamgifu.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2owfbkvzp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mokchqwz.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2lutvrikp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2hrbxppvp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqbxbqu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wsydcdib.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2noqujwyu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjlqyjgd.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2amagmhrf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2egnqtquk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2nrijoerb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2coyklheu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2mpcapbcf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hdqonsho.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwfxjhpl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2xpfyxwan.html


<!-- 参考信息 -->