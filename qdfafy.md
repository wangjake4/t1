代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2chqohtqn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gt2udufaniq.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2smccoliy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpjrkgdg.html

while (std::getline(in, line)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2jslwdmyi.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tdeizpyz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2rvxpizsm.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gt2hysshzrm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgvkkglh.html

[S51] C++：显式类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoxjssj.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rugqgsvr.html

[S52] C++：const 与 noexcept
来源：http://dali.zhijiandao.cn/Article/details/gt2tbcllrvi.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uuzvfbfm.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gt2caixdyxg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2txbuuydd.html

[S54] C++：异常处理
来源：http://dali.zhijiandao.cn/Article/details/gt2efvfcnpq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgazvwsc.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ijsgjhhd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2khjehndq.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gt2paasckbp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnlyxiy.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gt2dzozfygi.html

constexpr int N = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2metdxcjx.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2rprloqwa.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2loekiggb.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gt2twqbuhoz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvpcxai.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2kcgipwym.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gt2igvfmzmm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gsebutxy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2pyjenovg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2flhjiioz.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlxokgw.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2dlekkjws.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xerhmfqv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2uxiefjmy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gt2timdfxgc.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ywmfugxy.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gt2qexyckve.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmgshby.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2thwoknjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gt2etzlrxtq.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2bopnikyw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2trewtghl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2nfndzdme.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gt2ukszlend.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2vtoniiwb.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2jsfcnfnf.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gt2uhkwtzam.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gt2nztzwuey.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gt2xmccrpdh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kalpnadv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gt2snzyrqgw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2codkaptm.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gt2vysvjmjf.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wtybxjvy.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2mrnfasir.html

val m = mapOf("a" to 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ididfevn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hcxiudsf.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2nruzsjov.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gt2nhetjuxy.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2xboduily.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2djlgqzix.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2pqejpxhd.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gt2wurjezzd.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2miniieko.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2cghpmldw.html

"值: \(b)"
来源：http://dali.zhijiandao.cn/Article/details/gt2cvnkzhzx.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2aqejvutc.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gt2dkajzpyo.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rqqmhfgh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhijiandao.cn/Article/details/gt2xwxhbkwg.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ezmocmlc.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gt2rbgpcmas.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2ocdfythe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2mwvsrxas.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdfammf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gt2iiyrphis.html

[T24] Swift：闭包
来源：http://dali.zhijiandao.cn/Article/details/gt2xlrteqfk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2xmlwmyhh.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gt2nelsudtn.html

struct P { var x: Int }
来源：http://dali.zhijiandao.cn/Article/details/gt2gxmzwfma.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gt2yvpzliyl.html

class A: Base { override func f() {} }
来源：http://dali.zhijiandao.cn/Article/details/gt2beykfxki.html

[T27] Swift：错误处理
来源：http://dali.zhijiandao.cn/Article/details/gt2qoxhjtwh.html

do { try f() } catch { print(error) }
来源：http://dali.zhijiandao.cn/Article/details/gt2krgxuodp.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjudcljf.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gt2finsebve.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2beiroyjz.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gt2vvzxuicf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2kltptllo.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2mofvtdqw.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2clwscitu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2fsotqzuh.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2limvwank.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gt2gyzmmapg.html

[T33] Lua：表（数组）
来源：http://dali.zhijiandao.cn/Article/details/gt2dvipnqeh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2tellpsbn.html

[T34] Lua：遍历表
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqofffm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gt2smaauugo.html

[T35] Lua：字典表
来源：http://dali.zhijiandao.cn/Article/details/gt2hgovcblj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ywsjgqfh.html

[T36] Lua：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2vnzifwsb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhikjfr.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2vjqtpjwy.html

"a" .. "b"
来源：http://dali.zhijiandao.cn/Article/details/gt2kvaijbfa.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2emiywdgo.html

if x > 0 then print("正") end
来源：http://dali.zhijiandao.cn/Article/details/gt2dpupvmyr.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2evlbhbql.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2jorgbztw.html

[T40] Lua：元表
来源：http://dali.zhijiandao.cn/Article/details/gt2sqitnjbo.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gt2frijswxx.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2owpwfxtd.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2qqxggofa.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvyhzto.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gt2szkcbtbu.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2qhvkjomz.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gt2ioitjdrp.html

[T44] Perl：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2zqojepmm.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xiajqhvj.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2tsjrqjlw.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxxgqng.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2rqfniixk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2boneyrvu.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2ilvduouu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pnikainv.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2agjqyrus.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gt2tmztvpxl.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bbehdysy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwepboj.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxtfpatk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gt2fywxleew.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gt2unokmoah.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2lntptgso.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gt2hbewjgps.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mtwnjydg.html

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gt2xvftgzpq.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2jrgtqwiz.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2iieqifqo.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2mtujdvwu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2yfjxygfp.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2hpqnowex.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rpasaomh.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gt2vjbvopky.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gt2wivmlyia.html

[T57] Scala：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2vcbhtxmj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gt2cumdaljh.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqrrfdk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2lqmgpyxu.html

[T59] Scala：循环
来源：http://dali.zhijiandao.cn/Article/details/gt2lehzmxmp.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gt2hqbeojwe.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gt2biytclos.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhijiandao.cn/Article/details/gt2utcumzwc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bmeyrhja.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2tsoauswv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzukcvf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhijiandao.cn/Article/details/gt2rtqaxvnk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gt2ozjccwlo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gt2crohzifd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxmdhgp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfqassi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2banzstow.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gt2qswwyctt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhijiandao.cn/Article/details/gt2kxnpdtje.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gt2bafzfiaf.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gt2pbmowxbu.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gt2jglzfmhw.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gt2nhgkuwrw.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2klkvseqk.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2irhzyfrk.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2upcyrwur.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gt2ukyagjxs.html

[U09] Py：字典取最大值的键
来源：http://dali.zhijiandao.cn/Article/details/gt2sdhsrdth.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gt2linhckul.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnrwjfy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2zhgxltaa.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2komqtunx.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gt2xakjomxn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwkjkvq.html

Counter(arr).most_common(3)
来源：http://dali.zhijiandao.cn/Article/details/gt2rnhgffjx.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrnwlpl.html

deque(maxlen=10)
来源：http://dali.zhijiandao.cn/Article/details/gt2dlwbvekf.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2htgbivxo.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gt2efdmzmtl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gt2afldqyme.html

t = time.perf_counter()
来源：http://dali.zhijiandao.cn/Article/details/gt2fintgezn.html

[U16] Py：命令行参数解析
来源：http://dali.zhijiandao.cn/Article/details/gt2ffmzlawz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2snevpgeu.html

[U17] Py：初始化日志
来源：http://dali.zhijiandao.cn/Article/details/gt2hvzqmskb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhijiandao.cn/Article/details/gt2jabakrru.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gt2bismukto.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2qmqdvoxe.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gt2cryxpfkc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhijiandao.cn/Article/details/gt2qkxrncjq.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gt2ckueatoz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gt2yryzvnpv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhijiandao.cn/Article/details/gt2zqgmhilp.html

@contextlib.contextmanager
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjbdqwg.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrjtjvq.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gt2vjigiuje.html

[U23] Py：分块读取大文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoykfsm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2derwurtu.html

[U24] Py：路径操作
来源：http://dali.zhijiandao.cn/Article/details/gt2ssngfdzs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2yaakewlm.html

[U25] Py：CSV 按字典读
来源：http://dali.zhijiandao.cn/Article/details/gt2byrszilv.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2lltjphsw.html

[U26] Py：并发下载
来源：http://dali.zhijiandao.cn/Article/details/gt2wvojocly.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhijiandao.cn/Article/details/gt2ricatypz.html

[U27] Py：异步 HTTP
来源：http://dali.zhijiandao.cn/Article/details/gt2xcdasrpf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2tkmwehab.html

[U28] Py：类型别名
来源：http://dali.zhijiandao.cn/Article/details/gt2jzovueqw.html

UserId = int
来源：http://dali.zhijiandao.cn/Article/details/gt2jlsttput.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwbwhlg.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2gyvxwdet.html

[U30] Py：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2lycwairx.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2tavnhtxd.html

[U31] Py：单测
来源：http://dali.zhijiandao.cn/Article/details/gt2ulqzkypv.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2ksovccpa.html

[U32] Py：代码格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2jrnmclqt.html

ruff format . && ruff check --fix .
来源：http://dali.zhijiandao.cn/Article/details/gt2nybgvyzm.html

[U33] Py：打包发布
来源：http://dali.zhijiandao.cn/Article/details/gt2dgpsxflb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gt2brqtqvhf.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gt2mlznuppg.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gt2xfiozogd.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2bjkqijmm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiiprftz.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rtitmvfz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2nnzfyqsz.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaimwff.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhijiandao.cn/Article/details/gt2srdmakxj.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhijiandao.cn/Article/details/gt2dzmimmmr.html

Path(__file__).resolve().parent
来源：http://dali.zhijiandao.cn/Article/details/gt2khsxexdq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2kdxolpiu.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzzfrfh.html

[U40] Py：打印到标准错误
来源：http://dali.zhijiandao.cn/Article/details/gt2xrwwilig.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2lpswhqqq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gt2rfgzvgfp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2uwijkegp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gt2usbpphpb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gt2mhbkbcxp.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2ioewmeer.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhcllzl.html

[U44] PHP：开启严格类型
来源：http://dali.zhijiandao.cn/Article/details/gt2hhmcstre.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhjepwq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwkmhyw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qinikdxg.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gt2xuarekki.html

?string $name = null
来源：http://dali.zhijiandao.cn/Article/details/gt2vgdsnagq.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gt2pvnxlgvt.html

int|string $id
来源：http://dali.zhijiandao.cn/Article/details/gt2lcoovnyy.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmklhgu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ajjslqkm.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gt2ydihxidb.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gt2smaqekkf.html

[U50] PHP：构造器属性提升
来源：http://dali.zhijiandao.cn/Article/details/gt2jsrenugb.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gt2xsaqhqpl.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gt2dldikygp.html

[$a, $b] = $arr;
来源：http://dali.zhijiandao.cn/Article/details/gt2sthstyoq.html

[U52] PHP：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2diolwwkk.html

$double = fn($x) => $x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gt2pkaljhex.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2gfoolrhk.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gt2zehqujye.html

[U54] PHP：空安全调用
来源：http://dali.zhijiandao.cn/Article/details/gt2xntnknrl.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gt2tbhshwzh.html

[U55] PHP：match 表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmcfcsk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2lxgknmte.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ugzuxkmb.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2wzmymmqe.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2lgqpzqhc.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ujktawnc.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gt2stmhovch.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2vnwxkkbh.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2cpuebmrh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdeztgug.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gt2shwnyvqu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhijiandao.cn/Article/details/gt2sexuttri.html

[U61] PHP：正则
来源：http://dali.zhijiandao.cn/Article/details/gt2ohuizhbs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gt2zbrnjwix.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxsdogx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2snleyzwi.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gt2izmjphxk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzxyprdo.html

[U64] PHP：目录遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2gposajuu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2otocobpd.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gt2djomttxy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2chefedrl.html

[U66] PHP：设置 Cookie
来源：http://dali.zhijiandao.cn/Article/details/gt2kvocebks.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2xplicenj.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyscfti.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2mhjycmfk.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uhhnquns.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhijiandao.cn/Article/details/gt2hxeegyzk.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gt2xsthpzfr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyuzpcx.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sooilpqn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhijiandao.cn/Article/details/gt2yumhpexg.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gt2fhkzzukv.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gt2bmqmtonu.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gt2vohgtdac.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gt2ywvrjqtz.html


<!-- 参考信息 -->