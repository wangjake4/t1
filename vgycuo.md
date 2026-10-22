代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyefhfi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2aellnrgg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2ymwbibff.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cxzskjso.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2hztukyfr.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2avbxkixr.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2iixzgqkg.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2bifgkmvy.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2raxvmcng.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqhwqzr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2rubjbvey.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2retunjct.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyakuuu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2yyztcwam.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2sogfquwf.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2xraucwqw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2strsbwoj.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmsybjy.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2wrhdezul.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2mjfxfbpb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2xqysuxrq.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2akqofvfp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2ahqtobej.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qnofjvvj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2nuffkhtk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fjlctkqj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2jlllovxm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocjgcuec.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zinxzwgf.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2awsdakjk.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uczghciv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxpbfps.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2umxgbwhv.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xtrusrzb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2miebdeqg.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2ojedpvrv.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2fzozbxwi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dvwinxkt.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2dlgvzsjh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ljobebky.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2qkcroxqs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2gynroxbe.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lismnxjp.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2hpyqpvae.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zfshfyjs.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2wpggfgsj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2piepupcn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jnwahlun.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2fmcjfncs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajgirmuv.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2eclijuft.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2zvptogyi.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2wflswvcr.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2wmtyzyon.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2qbbgfadg.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2pmdreofa.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfrlxwg.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmvdbueg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ondpfqqg.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2cwemxbar.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2myeusgij.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2dphnohlo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2tvkhdkka.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwmqmxo.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2frjsdcgu.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2tzorwhat.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2mnyihecw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfqpsncy.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2etrtfprp.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2oisvjxsr.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2diwvyjdf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ishqwofn.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmtwpgac.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypkxisti.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2mxpdqold.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdmhpwid.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2rudmglrl.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2tdauwhkn.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2beapkzji.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjnjgbtm.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vhwyoirj.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2uouelcuh.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2kbvruwlw.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwkxvau.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nehouvnf.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2zjfrnoux.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2vlpmyzrw.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfivwtnz.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hpymdcln.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2wapctqsv.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2axjbsequ.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2zrycepax.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2sazqbpdt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2epixdmcz.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2wmkokyzs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2eeaipgru.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2slnksblr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ewuinsck.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2gtghfhox.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2xulpbzzd.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2qmgikmxa.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mrfoygfo.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymoymqxj.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfltefl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2uwpncppy.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sdjousmq.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kbrohkdy.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2jimaisxl.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ahcnecyz.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2umqfqpgd.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zgilzgfq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2klpcdfip.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqzexcw.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ugnqpwpi.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzejhfj.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jmdcbbvx.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ghufngax.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2aupvcogq.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rreetble.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yeqxhhwp.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2isxelnas.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xzivxqls.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sqiqfjij.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmahdevt.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pipaowzz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnhwytb.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfgvylbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2uptguqwk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2fvtqnmfx.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hicoqtma.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2exfbmajv.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cauyppky.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2svzhjoey.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2sctofnju.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2tippehzr.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2pfqbiwcb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2inuzelqn.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2zkutrreo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2iktnretk.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vnsaphtp.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuhewan.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bvleaump.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2vlnlfsyk.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xkejjcsb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2zfqbeefo.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2tblffyvs.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2xprwdfbw.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgoyzvg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2phritmuq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tyunpwbs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhilzoy.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2twkosyrt.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2teinmxkw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2czyjoxtj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkisimb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2oesqruby.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2egmvjlkv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2dqtfbemd.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2tfnnjdba.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2sasbkhtc.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2mnexqnjn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pyddlvzm.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2auxfynni.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2gyszqocl.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2icvrsjwy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2xipthmpg.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2iombpfeh.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2fsntfqho.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2xvxfosla.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwbxpuyr.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvjervn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2jvoeydck.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2miympygm.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdxmpmp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2qmalybvz.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnalfluv.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2snpgmmnm.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoagsplv.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2oddlkbik.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzzhnbu.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2lvppbmcc.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnkkyvs.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhgkubg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2pxvltmjg.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oujgfgjj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2egmckkcc.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2hvsqhfcu.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2eccgkgxg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2kmrsrzie.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2iaxissat.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2gtznhrpj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2zihoxirw.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2bvakdmvy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdjwern.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2egglylzf.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2taesqoxu.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ufdxkywb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2zsqzkebq.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2gjiyoonp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ibhrptke.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2smlgdnyi.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2qphfleip.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2crnzhzvs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2gukdczhr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2udbttdyj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2cauqyazf.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2yefzdnxf.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnrfzpb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rmbqxpko.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2zomagbkt.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2maekterc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2rekwwmcv.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2gjeyvqmt.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2pgizgteq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2pybmehwt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2rodcnrxg.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2atqnprfe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2xhhvrrvo.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2jeoicmow.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2kkxpbrse.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2oqsemwpy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2sbamfotk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2hjgtyxus.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2pumnjdlt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2jgeajdbx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2njvhgans.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqbgehf.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2hparonyr.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2idjjhdxx.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpplcjka.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zohwjliw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2cwfahsnk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2hwdbydzj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2wurmckuu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2piahumzx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2hgiwsklm.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ltzijenc.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2olcesmml.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gpfaewci.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2wqhpdslv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2nqegzwwu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jrqvufnx.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhddfeeo.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2qhghydye.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2agnmgnri.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfzayzg.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2gfofnlso.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2sldhrbcq.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2penhfhjo.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2rglbmspb.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2dqgyazpy.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bpsjnkcv.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2diglplnp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhlkmldh.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kguwmqfb.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqktipnq.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdjnant.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2agwqpixz.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgjuhul.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tcjceofm.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cikplxug.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2etzjzjly.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2pnrttyxw.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2ydrnewsh.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2spqdmimt.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jmpckhfz.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2wjrxbuii.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2nlpttrku.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2jexbsqul.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2plgumlmu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2yppehdrw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2mcbcirzq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2txqveeeu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2qlpjxmyb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2buxftpyk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2beuheamo.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2cpvmbjej.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2zgqhfpme.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtghavk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2epmjleqs.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2cxoxzqtq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2joctpjuo.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2tosiuuvc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdtpcat.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2ncttsgas.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2xpvaedps.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2eacfclaz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2mckinaeh.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2honrumfp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2ejkefysy.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2umzadpqf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2azcipvug.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnyipbt.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkcifnu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfksahkn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2csjvjbae.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2lbighxix.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2czxqmfdj.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rggedgtt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2jefebuoe.html


<!-- 参考信息 -->