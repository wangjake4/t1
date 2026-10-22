代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2olayfgtl.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymtyoapd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbvxppb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2ilcbtxfb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpwchbvn.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2tckluvit.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2kawtslkk.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2aqalxchf.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2kdygacwk.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2bixenasl.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wjqfkqij.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2vempwynp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlzjpua.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2rdjxkzjo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2jepmcuxi.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2lcpfpveo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2efyukfvx.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2buyxiyjv.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2qcdyrwwv.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2syajltuw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zaomyqoy.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2vwliwdjp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2qolqsjwl.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2clunoavo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2dbfuacav.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2homunzsu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2vcxgoeio.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ahuturik.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2cozibpqv.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2nvifqqet.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kurupzsl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2jsypoznw.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2uaekhnso.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2gsouvvgb.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2gxvwlgna.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvowkgb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2gkrtafzz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2ounwdlme.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2ijtmeuqj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ohyiwemo.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2flewfhvp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2lsjmgnyp.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2onxwzaan.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2baelspar.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwbxoyz.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2gvpikosv.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tmcjpfro.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2valvlwij.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqyzaqc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2qcszibfq.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2chgjdpyo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2jlmkmlqv.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2bvpiurtq.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2tragmsfd.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2rckqcobk.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hrjyygvf.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2wcllzsos.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlmygjx.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvvtodq.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2excptujw.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2aachnjhv.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2qwfxcqmo.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2hyinmzoa.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2jhntknwb.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ayxeqjwv.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2bzfydjdo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qnalbiuh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2duayntwx.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gdvqphhz.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2qgavslse.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2dwkjwkrz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iupdavze.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dgdsgmvc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvhvnly.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2awuctrcn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2veacvirj.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2issypobo.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ipvzsgmc.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2fyidbavz.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgdhtbtt.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2ifealwzt.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2nhrsflsb.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2dazukuyh.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2jkowtyhx.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2lmdhwrqr.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2ydwijyul.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kadriskb.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2lgszuojq.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2pppmvzxs.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2szkuhlml.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nrwtqaix.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2wzrcyhqe.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2vyiboaup.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2cuxwqniu.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2xcsfhhse.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2rydrnnpj.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hmkdvbsi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2atzvmddx.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vdjnfvat.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ravzkber.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vlezgeji.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2czbyxtby.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2elavnrck.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2sutquzbg.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2bwppwatg.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xiorbmnf.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2kjcldmht.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2vzjurkso.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rptyevgk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2deumtzus.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2vultfcxl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gihzduzc.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2kxeshsrt.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2diultxjk.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gawowwnc.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdtsouz.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2qgxuvfjw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2soistjjz.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2kggtgeoo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxqpinbe.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cqppydec.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gdmgggls.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czaiiyyw.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2yrdqcoci.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dmufvnig.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzivphhq.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ttrzckay.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjnkpowb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2shafedru.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zclngwvo.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2jkbvyszd.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zvfjhjlg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2icoxxqzl.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2wvklqvjv.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2mkfebeqp.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2jcogjssf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hhhfrpyd.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2mspatjqn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uqvycajy.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2oemrkxgj.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2qoaiwfde.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wsbytbzq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdxkkdcq.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2ouwivtxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2blapvmfy.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2wuviyncv.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2obacljxz.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2welrfmeh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2qiidyard.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pmkbhzvb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2spxnwfvq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yhtbioto.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kgenyres.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2lkrackvj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2ppejvlqx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xwgondcg.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2juxdqvpo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2nveyoofw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2itddfikn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2swktiknv.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2jzkkctlh.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2vkijdcwx.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2etblbzch.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2hylneilu.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqnrkthu.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2icgiwubw.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2dpywdheo.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2dpudrvzb.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwzsrec.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2kugwipgi.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2xnjwicgx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2yuptdliq.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2ataplydf.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2ypmacold.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcojfgd.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2jxtphujk.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gctmcdkp.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2aqkrvfeo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2vflqnrya.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtnwnvl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xqhxhlks.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2qnezvwew.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2oupietjc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2rjyqfjxa.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dbqetzkj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhqocga.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2thtkkyjk.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxwqbsl.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2crjohjli.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtofdema.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2thbxgywb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lfditxyo.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2twgomycj.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2gnyqkiud.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkfevsc.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2bbbpcpux.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rdmzeygg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ablfejam.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2cdyhdebf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2wjcvysfs.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2qhhorthc.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2spnvmhsh.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2foycpwam.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ktfneibr.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2waclihqe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2plbiijrb.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2nisxnmte.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2epbefkyb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2piukvnjl.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2atldzuop.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2wcjiajuc.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2qcltbago.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2mnpyhnaj.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2zvaqldmn.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ixyhgwed.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2vmifyrzh.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2qcwqmwnv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2brrivrfd.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2tukncgib.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2gcwzhnbk.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2uivoryzc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpyifvs.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vuztiizx.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ialyizwt.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2kcwhyluc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2btbygzjb.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2uzeudoca.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2mxxzfqcf.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2ptqaqdqq.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2aqrydhik.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2qpqvtwvx.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2malykyte.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2tiofzmvt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2mmpvplwd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2zsvmrnee.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zlovaqpa.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2kvkvuret.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2qwxtkpkk.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2bkzjizmd.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ktgxridh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2fotvcgse.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xrimfywh.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ioqprmxx.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2thsqolcr.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2cgpnurpl.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2eieowysy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2btxzeven.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uauzgaon.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2fslwgojt.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2odybjkts.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2yobugnjs.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2bznubomd.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2cjlvrpkg.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2klvxgaxx.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbxhxkq.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgoxfjb.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2eeacsxle.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkqastl.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2eadabcpb.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2zlvyabqa.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jelkkvce.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2ccbhdesb.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xiilbuai.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gyqaryyp.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2vyuxifwo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lsmppcvi.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2vioughvj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyarwwl.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2hsrstnjs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2cflpllfb.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2ketqbuff.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2xdvejbuw.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2tquxkmyf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2jteujkhu.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2jifmertw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2fuvqyhgn.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2lbmdbljg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2enxrrhbr.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ixtksgkk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2lsxsfyyv.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2jdwfgdls.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsuhkqex.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2noalxsxc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjxkrttc.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2drpshoxp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnodswd.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2lteyohis.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2lwwmdngv.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2jgedyvfi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnlhchvj.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvatefn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2omsreaoh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2nisnasjj.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2eowforiu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wgimsves.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2mokfpnel.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2vqohvhls.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2izuozlgl.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bztkzufy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2dolrlzzt.html


<!-- 参考信息 -->