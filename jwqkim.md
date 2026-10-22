代发 wailian999

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gt2vipmrzie.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhijiandao.cn/Article/details/gt2yldybogl.html

[S44] C++：引用传参
来源：http://dali.zhijiandao.cn/Article/details/gt2mwmaqzch.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaqgryx.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2owlpwugr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gt2rshebyli.html

[S46] C++：函数模板
来源：http://dali.zhijiandao.cn/Article/details/gt2xzqsdtwv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nzoxalwf.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2vczdzzll.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hlsegsxk.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eiuuvset.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvhploox.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2krkvclcc.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqefsfxk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ectorzwa.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2yfmhbcue.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnkpkeg.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2todowjtg.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbnxhxs.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2rsahgvwv.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iitdzplb.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2jleiqgle.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2girlromz.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jydnlxox.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffusstyz.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2liaoydvp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2zjucmdxz.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2znnazhdo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2rhmoqghi.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mleratrp.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bzbiinqc.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2phfbcywd.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlpvuwl.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2njsbbugp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2fecpxgtg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ontkjnsx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2hhpauxvo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vbbdxpor.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfcyapm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zopkrdqe.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oriaebtu.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2efobdhpy.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mklluavq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vjelshux.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2zgmijyig.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2juflsnoa.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2lgadzydu.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2cknuipgf.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eyaewzyo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2fmkcbolz.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2aegbfsgh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2qpxfqbij.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcemhfl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rshncbsl.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2mkcbrdyq.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkdmcwe.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dnlvdqzq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2bnzvwvxo.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oehoctzu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2eocvisvi.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2jhyrpwjy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkcuxuq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2nmackurb.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2fanfdujw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2auvthkwt.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuxomlv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lkhpgfou.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hskdrpcr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2iddzscxl.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2vkpljmup.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2sqxsuevg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pcblxwwz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrlmzot.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2atmluaoi.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xzijzgfh.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrierrlv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2drgwrxvv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oclcwxio.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pfardxhh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2aiavbhjf.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2jjokgyqf.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2hrignznl.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2storphbu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2osxcmezr.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wxpqreqq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wmraxibm.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2rguitimo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2jssrinmy.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2tvrtygio.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2qmvuqshg.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2erzyrfpt.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2usvrdlds.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvncesx.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ldvqfjtj.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2joachuty.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2gtdnpaae.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ampmlntm.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2gheagvas.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2rndjijdg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2hqeqfbpt.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ootutscg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wrklwrwu.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqkdlxo.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zwfjtagn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2urywfudz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cwsmjmvz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jsmfgxmi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2dbubmdoe.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2unlsesoq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ldauyypc.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccftbuvf.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zjbpaztr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wltcffvi.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltjuujjm.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2voutipuo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2pnlodqpt.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2hgwwralm.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jzuistsj.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2jutyhpin.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2xgkuukua.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2znsflcvs.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2pysvfarh.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2feiqrvfa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ixhoulkj.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2gmfjbwfd.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2kwkuygsg.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdffewa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2whpruyoc.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tprwsjxw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlmmsctb.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kdgpacjs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnehtanc.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2kdhlexff.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtzxuwb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qpsfaupr.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohwdzqfh.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2agfmhyyj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wvtirflu.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbfwpyzt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqeexxa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nxozcrcj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2vdfmhidj.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2rzqtvodc.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eanenfyv.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zrpbnzqw.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2drptseej.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzrygaja.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwsqemm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdpurhr.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2xvyvicso.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2nqrqiams.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2ixpcgwop.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeeijpt.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2ekfhxhhb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vofitblv.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xthjhzus.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2pirhnvfq.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qymfdmoo.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2yapyslcw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2zfpthafk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2kecapilz.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bgdbhmsj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2qwdowwil.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhwbytr.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2fxssldbi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2oorsgfme.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2lzlnkuoi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xpzpryil.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kuxlrpyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2zuuqxfcs.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2wtcsqfyu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2bgzvyoyh.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2brhuaibw.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mshnzpiw.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wmfwusqa.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gzmpcaoz.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2ohgbzzro.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2pisxtcbu.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2sxzevmib.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2vspcrira.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uoznqaya.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2nzpwhayt.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rhacwyyq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2afmmebau.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ikoovbfb.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmnigswl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2dhglrinx.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuxxlzz.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmrxebh.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvcbdexq.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2hekwyphl.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtodlepv.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2agrgrqzt.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2bivszvxw.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2kqyczwgl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2lxthjycn.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fymvuqrl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2klhqrjyz.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2gdotustj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2oxxasqjh.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2wjvdvcqz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhwscwxp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ugdmjoei.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtbrovel.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2lescdlqu.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2bgircbgu.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2htplpgle.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdxvxsj.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qubuamwd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2vnlxkwcb.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2nlimiksx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tknbpflt.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2txjbhzos.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2npwwyfom.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2zvvfoyag.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2admobtxd.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2vlsidruw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtfafes.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2okwuilue.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2vbojbhxy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2faljovdf.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2amfsszih.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xtfhczze.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bscmplgd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gvbxjgur.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2hioxyiah.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2fsuqiotw.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gpapydda.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2hxzvntzn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2altltcqu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2snavlhvp.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2zualoqkz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2udrbmmre.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2kilnavxf.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bepchgvo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2dxiobsqi.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tujnwvyy.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2wkyqayzd.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qxeoeuly.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbynjtr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2thvwyptw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2csvsaspb.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2vtrruylc.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykdnvsgj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rifsfekl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2zngeqzsk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ifydinsq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2ffhklgbe.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rciyvicv.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciixbljv.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2sbdnmqfp.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2dsrwxitc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xmtrqpet.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzlmnhot.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2yvrdcyol.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2bdnwcdez.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xvharliz.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2hetobhra.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2cvbnndxz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2muhwxnhs.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2szjwnjxl.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2mrkapiim.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hkjkyycj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmakfxv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2juplvozi.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pucvxazn.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsjorot.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fccpzxgn.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2ejcmmbel.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2blobigln.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ooqrukrn.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhawbpd.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2uhcfyoiy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2sztsolow.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhrjbzv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2nrvmsgoh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyjjsub.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2soutbyjm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ijwzkqed.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpfhugy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2bpfbagkm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2plhehkdt.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2aasmpcev.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sbnhhjup.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2caffgogh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2oynjhfwp.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2lopbfqva.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2nmkcejdd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2aktoczkl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2asszuscn.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2alfsfjwb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mvkylqpc.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2odexkpuc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2uajpodtl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tuyrznnn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqenfcc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2zwsqrzxe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdzceoc.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lalkxqyy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfmhbzo.html


<!-- 参考信息 -->