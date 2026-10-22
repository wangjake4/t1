代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2evrudryf.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xvoixlua.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rucucyor.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2hhyppyas.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fuaibgre.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2xioxsnbe.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2amiblndc.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2oljgyygl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2xphkowsd.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2zxreuhjn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjybpwl.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsliopq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bqmrjbyl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xgddvlbm.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dxdvcbtz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zfeyzthq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwbpuyc.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpbhgdq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xiccccrs.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gesfhnio.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2olbpjech.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsmivtk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2suxtlwjj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2astwtstw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2srzugcfb.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hnccfxzn.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ptdmgmxo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2qghxaieb.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2rnuqgvqr.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzafquq.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2svnhgrvt.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2pqskgijm.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2aprogpef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2vpbuukcn.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2seaytmwh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2fbnvqvrg.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qxzqmlpk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2yymdcrtd.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvqhyej.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2htfjapjm.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qdssefjl.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjjqstwx.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qlmlnpfh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrcvqoy.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2xycbuwpp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2eveawmoa.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vwqsavma.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2skopvmwo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qchmliti.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gehfrcpv.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cvqmydtj.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2khglrthr.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2oznrcpys.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2otwkhrgl.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2tkhjobip.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxldleou.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xewlznoy.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gqquksws.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pfzqrxbc.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2mumsqfez.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2nlfknujb.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ortgvlyi.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bsoqbxbe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzbucahp.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2oxnhnqik.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2mugnhzdk.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2mxswrnsd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2rphvxsfy.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2djlajufb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2guefetfo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2fvftnjry.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2esvnobub.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2ecuhavqk.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2xziunkfp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2jzldftjh.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2okhehfqs.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2bwaqsgko.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wzpzutim.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2qwhdklqn.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2hwohbbmz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2fqladrom.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2wlpjljsn.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2sihmqqhu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlhyyxdl.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ebaabkfr.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2kantldeq.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kiqvugkt.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2huaqixnn.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2laxitnxc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2rrocwmuo.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2jwulaqch.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2fonwrvrs.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2liajcyki.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vjkqkjkk.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2xrgzybln.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2fswxtzpk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2reswpzgv.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2hbytwdzj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gmkkdedg.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2nweegyte.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2eexqztrj.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfjyfic.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2adecfdot.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2ygjwkfoe.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2umyxmhbw.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2yhwpbcju.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fqjmyvdp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblgttax.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpslbvnx.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2bbjhbkla.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2poehmxql.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eahoydkv.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2xgigxcta.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bunadfmp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mwizppph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2douiwmjn.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2smjgltqe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gsyeuwes.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2buaabaou.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2gmgbcfck.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2celeooye.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhwkvqv.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ztdvukid.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvajwhuw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ckqsbzcj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2buulgpgz.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2gxcaiojd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wbbkmglh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nvgfukhn.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sftobxyo.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xcgigzqf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2xlwnykzc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2frxgxnrz.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mryinyot.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2opuwifua.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2wlbkdnxs.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxlhuau.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfheswgx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdozhwtq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbffghc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2erenezwk.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lkjrupvw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vhsbyoog.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2imvocmcu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbosfogg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eipbfzxb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2usoyouro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2cdxyognm.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2jesboydn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2swbcaace.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2qkortelu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2cumvflai.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2oeryofuo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2udtitzlx.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2mufzuzxz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kxjzhvgw.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2hajasaxo.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2eexlflqa.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2szmassvc.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hwkhemjk.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vptvjlpl.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmkspfv.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2cstczawk.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2btbplqki.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2wlkouapu.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2vehwyhhy.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xtkanugd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yxtihuwq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ipbyjfwh.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoiksyi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2xvzarwgh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2ueoetqoy.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2quamapzl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2pedczwlm.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vncwqupq.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2lhqtdqqo.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lquzsxzh.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2rpxbykwn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2uvpiqsdg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2degtuohr.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2rwqprehc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2vohkrswb.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fgrdyykz.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2cohypfrg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2urxqsnis.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiwipuy.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2cizekgtb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2nbarojfp.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2fdxjhsen.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2udqwwygc.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2cqrmivjx.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2zyombgbx.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vqaemdve.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjbtuok.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2luwquzth.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2htnraouu.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2imouajun.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lotpodzd.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2qrbqqxhv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2pienwmly.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2dttpgepl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wbpejcfs.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2mbgqjych.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2hxtdsjdn.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hsfamjwl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2eybproku.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2quvvggtm.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2fadjxpqm.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2qlhmzfxk.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2tojrchni.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjsydlm.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2hsjfzwic.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2othghapk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2djvwhubd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2uztjfmnc.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2shkqvnxc.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpdlwbv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqhbvqo.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2nckmbusx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ockwmxop.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2flfknxnz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2gnwsxhme.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2hrnujadl.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lqekyikz.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2xwnhrjvo.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjzcvzef.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2bqstrzwi.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxpcdjcs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuhmkbm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wbdwnxid.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2dspibeae.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uquiszwb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2szlvjaxx.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2olxzanvs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xkqjuhpk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2yzoxhdqc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofphdvxv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpmsqprg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zpnxatpo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2asdxduga.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gqcugnov.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2kmwxtarr.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzlwjsu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ybudnayn.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2msasilne.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2metmpiup.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2flezigtc.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2onkxufax.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2vcykdfll.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkcbsnfx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2eetftzqn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2vbudeulw.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2wnheoyok.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2djzzcsau.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2uwoajxul.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2xoehromm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2dddtbflq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2vwebyhqj.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rszvngrn.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhpyrtrk.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2dinyzbxw.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ddgvttuv.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ndanpdsr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zqlgvczr.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dycafemu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lybqqgnn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2mbrrrygz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2kxoddaai.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2zjgupofq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlgrhgs.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rnkdlmgb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtvpyult.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2qwmbhprz.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2mkuoxouf.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2pisfhefm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2jiyydeiz.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vmyhylnc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2knmdtuwg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2skfrbdrh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnoaoixn.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2owwzjylf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2jroxfjjj.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2jtfmrvta.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2cjknnupf.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kcbazcir.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxtfisl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2oxptyaeq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2sdowmese.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2eooxzsiv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2gcardlol.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2gdioyapd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2sjqkrtvo.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2axqgphar.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2afqxyfhz.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jtqnaftm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2urbwlzep.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2vehfnuqd.html

composer require psr/container
来源：http://dali.zhijiandao.cn/Article/details/gt2hgastogg.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2mxftxvdy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhijiandao.cn/Article/details/gt2epfipoyp.html


<!-- 参考信息 -->