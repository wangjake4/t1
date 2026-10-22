代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjrhgvb.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2excysnoc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2fcgyyeke.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jynbmsnv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2wnhnnqqb.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bhjfmlpl.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2zcfghrza.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2ujvxfyqt.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jixzcicd.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2rxaftort.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2wfnxuijn.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2kzumfjrq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tbefusnw.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2tmrsgocm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypodgsfc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2ipojbrav.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pqodoimb.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2xkxpjvlt.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlvawpw.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ieymwrld.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vcsvhltf.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2qbopjhzv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xsnkchuz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2gjuswqcd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2ecipuvii.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gqfdwyhq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2siuvhwue.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrhyeek.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2dnqepepa.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lldirmcq.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ikpdwrvb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2trwihkme.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2excsenir.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2bfmocqvu.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2jldzzlby.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hwuxkadg.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2xufwynri.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2yonkhksj.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2hmnntvte.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2rdpubnji.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ftovaztz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnxxfeld.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2dccloplb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2uuuywehl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ypajgssd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2ixrfpboj.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kcykbvcm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ocairvxu.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsendqd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2cepnnyvh.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2fvllyweo.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2oqejtqln.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2qglcpuxc.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gamegaid.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2fdulmfpo.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2dgwpfvmi.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2jgltyvcb.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2diukcpwd.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qlndkdch.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2uoxwbwft.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2irogifxj.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2apoikuxs.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbwkateq.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2vugbnoaf.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2snuzoowz.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2yhlxpzeb.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2pisipxdd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2zxgvugzv.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2mfdqscxy.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2xasijmyg.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsjocr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vzckahbz.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qyfingzb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpgoizir.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2eplrueea.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xlagwvkf.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwlcger.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2ebssahsv.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2rcujniiu.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2rjmnlybf.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2zecisrpd.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2ksqcrvfs.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ggtroeqq.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2wspdwkcp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2ldklqcww.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2uddanqnv.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2hpjfdhtr.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2qbzuiepm.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2uvtmzckm.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjdkrex.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qathurik.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2rjpbbjcm.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkhbfwi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2hdmdqlcb.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilywokxa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2nysxhgrv.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2onsxuvjx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2swofdpdj.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2alabxosb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2ckpndxqk.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2twcglnji.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2xfzlvrse.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pmwyfzef.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2rqefzepl.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2luhrdhol.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2biwkafww.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2nrlciqde.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2qpoolbjg.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2licrczvt.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2roisevex.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2thivfenc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2ypveifjo.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2fbtupqjs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2htcvsegl.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2smvuzikt.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2obvwdbog.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2iagjvcko.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yvouvrei.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2qdbkcegv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2svenxilb.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ofmddrqq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jevtqubb.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bmiwxzba.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2oemmnneu.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2dvjrxsal.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pgpuudce.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cplmvzsl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2etzsiqfs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2oczvapyl.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzrjpwd.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvgihjp.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2npnlkelh.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2sbvjymep.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2rmtpusfx.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2loixlpvs.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2rakkdkjh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2gmhxslim.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2tdlfwfqy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2etjuhwgh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlziect.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubryqjgz.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zgrylpgb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2ivfzutqm.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2kzcunrsa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2cmuoeaaf.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2gpgjguir.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2lapzxqau.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2xmwfmfqv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2krrwfmvr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nlrxfltv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brflpkcp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2klssnypa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2vqgijekj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2tjimkcgb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2duoxxgtw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qajkypgn.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2kguxzgsr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2ziscktba.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2luqttcyt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2fxqtfyol.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2namsxnna.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2mfavarpr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2rtakgubq.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsytfuo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2dvsefppt.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2bfgftfeb.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2xajgcxpc.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2mvatotmk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2uaiovxca.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2uzemqzih.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2cbyejspv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2itschtys.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2svoghzld.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2gielvoos.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2slxxeype.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rrcwsuvw.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zovlkpry.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2wnjsrbuo.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2qtfxdthf.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2jixsmtno.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2xunknhaw.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2njhuacph.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2iazkhwtz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmlztdj.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2wejizdxb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqxujuf.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2obcqlywd.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2pitpdekk.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2femlswll.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lovupigp.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2udqvdmtj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2lljnzjli.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeiczcy.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2yswjrdcp.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2nhehhcsh.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2lcedrfig.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ndyjtcnu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2rstqvijc.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2fpzwhdoa.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2ytclxwgp.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2vtnauxqs.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lerjvfyf.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2gdolwihr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2epgqiunu.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2evjslllu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2wjhluarv.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2piwylbix.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2bsluibbe.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2zydbgcax.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2utoxcxtc.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2rwwkbtaa.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2vtkezady.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2wnryjlbv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2dbceuliq.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2myyximwd.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2efrfvtth.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2ytzwretx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2iismfpqv.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2zrdasdrv.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2ykmxicqz.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2xzucymfq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2pxoeeckk.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2lesnvzpd.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2ewidhxmr.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ztrlhyhn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2hbmheonv.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2sshvlict.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2lmbwklsy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2dnjckfwv.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2yuedlyag.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2nqfztabr.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2heairrij.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2qiuhmgar.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2rzizljrv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2ghspbvpn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2uzjykutd.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2jnikxser.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2dasokdhp.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqdrjfa.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2onfcqclv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xrvnqcqe.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pvvmpgnq.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zryffapt.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2okefekrw.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2zvcxxdov.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lvydynlj.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2wvycnatr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2clgkkosa.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2xqijhlcz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2dcwebuig.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2hvuefqrp.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2vdyhdoqk.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2fqugqrck.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2uyzoafyp.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2almsvuyn.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnwaomcz.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gardwutp.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2xbxcutok.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2drufciko.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2jsnjnigz.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2cctklspk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jopvwdvy.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2oavnxnsq.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2auupxnhi.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2meohprxe.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2famieney.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2iqrxjpav.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ipurkpmd.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2erhmtbwn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2argcfkwh.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2jdkihbcl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2jucwncxq.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2fkbonycr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxltircx.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2rgquaqpc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2jmnewxpv.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2kcrzkqin.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2gfpkzyae.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtmliir.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2rysalnqu.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhpeqva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkpgsar.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2sbuahqdo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2qtgwwmeh.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmivapx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2lizoqffx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2mxyryjni.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2jodctisu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2eianlaer.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xgakwhpl.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ndfttfbn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2llsdzzgh.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2wkhlwkqg.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkvqprox.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qcbndnuo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2qpeupdrs.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ohcifmmy.html

parse_ini_file("config.ini", true)
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxefcib.html

[U74] PHP：读取环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gnictrou.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhijiandao.cn/Article/details/gt2wdkrhnpw.html


<!-- 参考信息 -->