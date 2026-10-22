代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2esntcrsu.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dvmcpqju.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2mnbscfip.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vgevpvva.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pjkvhgrm.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cxdmwidt.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2qvehtxui.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2kkpuqglu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dzicdmyj.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2hpvlznpp.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wwjlcwvj.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eovvefdw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjqcfxa.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2fztijruo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2awfugpbk.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2mgwbfasy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhcnzlfo.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2lwqpjitw.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnbfzbhz.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2cfrnjecu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zgoddgyy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2xlullhjg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2uaivuyej.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kdoviuil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ifiknrqo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2oiqakgkl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2xffkhivh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkfejzw.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ayiiyhxm.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2mehhjmva.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nfxiaeai.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtwhxot.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2btpiacnc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhmrjzut.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2pvmuapnr.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ycqsgmbw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2tjhkksef.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xttfvtqr.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2lyaqyalw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvvnlue.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2vohxaqhz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrffulw.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2yszddins.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2mpmhytck.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2hxyxnwxr.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wilquetn.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2qnpmsqat.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ssyprcsp.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2rsmvttbg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2rozwdgzn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2lqfvxswe.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ihwzzhgk.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2fpbcvsjg.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2xunznwpf.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxcszhg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2vuazwove.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiobiew.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mipukcfr.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rcojtcin.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2yqtqlpjq.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2shaohyql.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2bxrdalik.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wnselnfw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2gjzxlssw.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ogtnynwl.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhaijeuj.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iqiiwdjc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlggpnx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gflrwcfd.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tyzrfcpp.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ohlhvshy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2hbeytsag.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiirdfo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2uttsetuo.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2jydgchgm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2vimijsky.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2vuhklryv.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2bkacsvyp.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2vxijvxqx.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2htmafltg.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ogrkjsqc.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xjvjcuen.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2rulbttcw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2fabnbyjx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2sdwsyvmf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ugufsfqu.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2ewmesvua.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2dblfhlok.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkstlec.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2ymsybyie.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dklnsxje.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gqjfkkpa.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sahrlcex.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hyckqdwd.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2acgzccge.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2qtspxbix.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2awbubryt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kljxwwmv.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2yjtcnegq.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2zqygemag.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqvjijy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gadvybsj.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gnbtvoag.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2gnrwekuj.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gprjcpuq.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2syeemskk.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrdjjlj.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2zysoztza.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzjarrc.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ljmxlxqx.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ryifzboh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2mzzdodfy.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2zadzxhek.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2flhkfgva.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2urnuktsa.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ikxovjzy.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2eahmlnfw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2odycokng.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2efutmhvd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2heqmturm.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvwjmwp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2alwzublo.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jpctkduj.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2guqmtzgr.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2mzsnysup.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mcersgpf.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlscyld.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2ugootqmx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hntldvqj.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uaupcjpk.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2afzafkrh.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nzhzlllq.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsjdwyv.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2pwkifckz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2rtgbnddf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2sauouxrk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2szubqltb.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2bouhxakh.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjfnvme.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2fzfymamo.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2sswbrokm.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jutktlik.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2otuserjh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ibsdiudq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2veokwqab.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2loaolfve.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2mxnkjsra.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2pemhxyjv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbkurem.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mvnhzizi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2kofsxiac.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ljvgqfbk.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2pwrnaqle.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2cezzmugm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqqgsqc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcjsqfl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2wounnasq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2oqssprvo.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2ygsvbmsq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2hwzimprj.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2oxjlgvjr.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2fbajdled.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vznmfhjz.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2dkcivunw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwlwlek.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dtohqkkb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iqszgtep.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ltasactw.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2pugznrkm.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2yvenrjxs.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ovyfikrv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2pybcqvwk.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ldmfdwxa.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvvfjamx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2feawijnh.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2feapfhii.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2trfnqaoq.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2olpimxdo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2kepzunra.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2rtiglmiu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjyxyku.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2jnlwwfyj.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2vrazqnge.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pcrkuihv.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vuwzsqfc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2wneaudwd.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ymcohogj.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2iaqdgezy.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cvxfeunz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2aaovhadd.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2qiiawxij.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfewctls.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2njrbaxqw.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfleqye.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2lekohuve.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2ispguaqk.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vvayiwwj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqmfzhw.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2hdipmlcm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2lgljswfk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2cvjzlffo.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2uklwfhiw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2hmuakcde.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2fihjcddf.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2mxoakitx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2dewahzfl.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2kilqfwac.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2ckcvikku.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2fkmgcdlv.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2ishademq.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2aysxayje.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2bfnardwb.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2nvbplmoy.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2lwiaztqs.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kekxejyd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2gldedwes.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2wsusfdis.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2fvjgvalu.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjzbccu.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2qfclbqkb.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2wfxykbpa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2ppyzrddj.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2avhnwpmo.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjotkdxb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2uvddancc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2cdsyjytg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2zhtbrxfj.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2kskirpmt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2gkxqmabg.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2feyiiccu.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zpxfxqyq.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ghvrgmrs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2bkfbrxwn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2hkpmhhhp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2uzxqpsyh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2sakdfprv.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2uuseduwy.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2lhrrgigs.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hekwswlk.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2zavotnxb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfspzdk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsftzui.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2juxgmyyk.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2sqcupwts.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2wqbfvtrf.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2fuljvhdd.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ilyrsvgd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2akkuesqt.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2mxwwxzvf.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2vocyzquc.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkuxlnj.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2jlkjmskc.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2ublgyvxe.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2dwtervxf.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ighfwvkq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2rsthxmau.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2szquwiwi.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2cphrrqgq.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2speauznc.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2ulmbdrsw.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2mtmandug.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccpbgzvy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hnklgqyv.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bjwfqtlw.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wprharhj.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lfejfnuc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkmcaoy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2aqgcdjpy.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dhjwunkj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2eblilmaw.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2xwiarpth.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2ntfuguqh.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tzsifylk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2nuhpshto.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2efvchtue.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2ooezlncy.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2okgdgrha.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpkynod.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2npuabayp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjofkcp.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2xcalrpgf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2eboendgq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2moiwjtkb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2rzggtyol.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2kwgbuglv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2krkcgkln.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2hovwlljp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mthnwwtj.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2karvhtfe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fbvihqje.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qoomfxxe.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2orlhkoxb.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2xdyaqdod.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoatpgs.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbhstgvq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2jqqzosel.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2eaxrgweu.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2nsjomslc.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2susxordp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2woqweoof.html


<!-- 参考信息 -->